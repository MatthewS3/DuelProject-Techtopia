<template>
    <div class="container99">
        <div class="row">
            <h2 class="display-2">Product Details</h2>
        </div>
        <div class="row">
            <Card v-if="product in $store.state.products" :key="product.prodID">
                <template #cardHeader>
                    <h4 class="card-title">{{ product.prodName }}</h4>
                </template>
                <template #cardBody>
                    <p class="card-text text-dark bg-gradient bg-dark-subtle p-2">
                        Quantity: {{ product.prodQuantity }}
                    </p>
                    <p class="card-text text-dark bg-gradient bg-dark-subtle p-2">
                        Amount: R{{ product.prodAmount }}
                    </p>
                </template>
            </Card>
        </div>
    </div>
    <SpinnerView/>
</template>

<script>
import Card from '@/components/Card.vue';
// import SpinnerView from '@/components/SpinnerView.vue';
    export default {
        components:{
            Card,
            // SpinnerView
        },
        computed: {
            product() {
                return this.$store.state.product
            },
            /* eslint-disable */
            fetchProducts(){
                $store.dispatch('fetchProducts')
            }
        },
        mounted() {
            this.$store.dispatch('fetchProduct', this.$route.params),
            this.fetchProducts
        }
    }
</script>

<style>

</style>