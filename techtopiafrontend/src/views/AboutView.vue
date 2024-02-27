<template>
  <div class="about">
    <div class="left">
      <h1>About us</h1>
      <hr>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

    </div>
    <div class="right">
      <img src="https://res.cloudinary.com/arpr/image/upload/v1540359700/adult-affection-baby-755028.jpg">
    </div>
    <div class="clear"></div>
  </div>
  <div class="mission">

    <div class="left">
      <img src="https://res.cloudinary.com/arpr/image/upload/v1540359700/adult-affection-baby-755028.jpg">
    </div>
    <div class="right">
      <h1>Our Mission!</h1>
      <hr>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
    <div class="clear"></div>
  </div>
  <div class="team">
    <h1> Our Team
      <hr>
    </h1>
    <div class="card">
      <div class="circle-container">
        <h1 style="color:#fff;">M</h1>
      </div>
      <h2>Mahesh E U</h2>
      <h4>Technical Lead</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
    </div>
    <div class="card">
      <div class="circle-container">
        <h1 style="color:#fff;">M</h1>
      </div>
      <h2>Mridul</h2>
      <h4>Evangelist</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
    </div>



    <div class="card">
      <div class="circle-container">
        <h1 style="color:#fff;">R</h1>
      </div>
      <h2>Rajesh</h2>
      <h4>Evangelist</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
    </div>
    <div class="card">
      <div class="circle-container">
        <h1 style="color:#fff;">B</h1>
      </div>
      <h2>Bharti</h2>
      <h4>Evangelist</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
    </div>
    <div class="card">
      <div class="circle-container">
        <h1 style="color:#fff;">A</h1>
      </div>
      <h2>Anhsuman</h2>
      <h4> Advisor</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
    </div>
    <div class="card">
      <div class="circle-container">
        <h1 style="color:#fff;">S</h1>
      </div>
      <h2>Shruti</h2>
      <h4> Advisor</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      </p>
    </div>
  </div>
</template>

<script>
</script>

<style>
.about {
  padding: 5% 0;
  width: 100%;
  height: auto;
  background-color: #ddd;
}

.about .left {
  padding: 2% 0;
  float: left;
  width: 50%;
  display: inline-block;
}

.about .right {
  width: 50%;
  display: inline-block;
}

.about .right img {
  width: 100%
}

.about .left h1 {
  text-align: center;
  color: tomato;
  margin: 0 0 10px 0;
}

.about .left hr {
  width: 100%;
  border-top: 3px solid #000;
  border-bottom: none;
}

.about .left p {
  font-size: 1rem;
  margin: 40px auto;
  width: 80%;
  color: #000;
}

.mission {
  padding: 5% 0;
  width: 100%;
  height: auto;
  background-color: #bbb;
}

.mission .right {
  padding: 2% 0;
  width: 50%;
  color: #000;
  display: inline-block;
}

.mission .left {
  float: left;
  width: 50%;
  display: inline-block;
}

.mission .left img {
  width: 100%;
}

.mission .right h1 {
  text-align: center;
  color: tomato;
  margin: 0 0 20px 0;
}

.mission .right hr {
  width: 100%;
  border-top: 2px solid #000;
  border-bottom: none;
}

.mission .right p {
  font-size: 1rem;
  margin: 40px auto;
  width: 80%
}

.team {
  width: 100%;
  margin: auto;
  padding: 5% 0;
  background-color: #ddd;
}

.team h1 {
  text-align: center;
  color: tomato;

}

.team h1 hr {
  width: 100%;
  border-top: 2px solid #000;
  background-color: transperant;
  border-bottom: none;
  margin-bottom: 50px;
}

.team .card {
  padding-bottom: 20px;
  padding-top: 20px;
  position: relative;
  min-width: 20%;
  height: 500px !important;
  height: auto;
  background-color: #fff;
  display: inline-block;
  margin: 40px 6.5%;
  box-shadow: 0 0 20px 2px rgba(0, 0, 0, 0.5);
  text-align: center;
}

.card .circle-container {
  position: relative;
  background-color: #579f79;
  width: 250px;
  height: 250px;
  border: none;
  border-radius: 50%;
  margin: auto;
  color: #fff;
}

.circle-container h1 {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  margin: 0;
  font-size: 60px;
}

.team .card h2 {
  text-align: center;
  margin: 30px 0 0 0;
}

.team .card h4 {
  text-align: center;
  margin: 10px 0 0 0;
}

.team .card p {
  width: 250px;
  margin: 30px auto;
  text-align: center;

}

.clear {
  clear: both;
}
</style>