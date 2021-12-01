<template>
<body>
  <div class="container">
        <!-- Menu card -->
        <div class="menu-card">

            <div class="card-report">
                <img src="./assets/images/image-jeremy.png" alt="image jeremy">
                <div class="report">
                    <Tracker report="Report for"/>
                    <Tracker nom="Jeremy Robson"/>
                </div>
            </div>

            <div class="menu">
                <Tracker freq="Daily"/>
                <Tracker freq="Weekly"/>
                <Tracker freq="Monthly"/>
            </div>
        </div>

        <!-- Regular card -->
        <div class="regular-card work">
            <div class="property-card">
                <div class="row">
                    <Tracker title="Work"/>
                </div>

                <div class="row-2">
                    <Tracker hours="32hrs"/>
                    <Tracker description="Last week-36hrs"/>
                </div>
            </div>
        </div>

        <!-- Regular card -->
        <div class="regular-card play">
            <div class="property-card">
                <div class="row">
                    <Tracker title="Play"/>
                </div>

                <div class="row-2">
                    <Tracker hours="10hrs"/>
                    <Tracker description="Last week-8hrs"/>
                </div>
            </div>
        </div>

        <!-- Regular card -->
        <div class="regular-card study">
            <div class="property-card">
                <div class="row">
                    <Tracker title="Study"/>
                </div>

                <div class="row-2">
                    <Tracker hours="4hrs"/>
                    <Tracker description="Last week-7hrs"/>
                </div>
            </div>
        </div>

        <!-- Regular card -->
        <div class="regular-card exercise">
            <div class="property-card">
                <div class="row">
                    <Tracker title="Exercise"/>
                </div>

                <div class="row-2">
                    <Tracker hours="4hrs"/>
                    <Tracker description="Last week-5hrs"/>
                </div>
            </div>
        </div>

        <!-- Regular card -->
        <div class="regular-card social">
            <div class="property-card">
                <div class="row">
                    <Tracker title="Social"/>
                </div>

                <div class="row-2">
                    <Tracker hours="5hrs"/>
                    <Tracker description="Last week-10hrs"/>
                </div>
            </div>
        </div>

        <!-- Regular card -->
        <div class="regular-card selfcare">
            <div class="property-card">
                <div class="row">
                    <Tracker title="Self Care"/>
                </div>

                <div class="row-2">
                    <Tracker hours="2hrs"/>
                    <Tracker description="Last week-2hrs"/>
                </div>
            </div>
        </div>

    </div>
</body>
</template>

<script>

  import Tracker from './components/Tracker.vue'
  export default {
    name: 'container',
      components:{
        Tracker
      },
  }

</script>

<style>
* {
  margin: 0;
  padding: 0;
  -webkit-box-sizing: border-box;
          box-sizing: border-box;
}

html {
  font-size: 62.5%;
}

body {
  font-family: 'Rubik', sans-serif;
}

body {
  background-color: #0f1424;
}

.container {
  width: 88%;
  margin: 2rem auto;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  gap: 2.2rem;
}

.menu-card {
  background-color: #1c1f4a;
  border-radius: 1.6rem;
  width: 100%;
}

.menu-card .card-report {
  background-color: #5847eb;
  border-radius: 1.6rem;
  padding: 3rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  gap: 1.8rem;
}

.menu-card .card-report img {
  width: 26%;
  max-width: 130px;
  border: 3px solid white;
  border-radius: 50%;
}

.menu-card .card-report .report {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: flex-start;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  gap: 0.4rem;
}

.menu-card .card-report .report p {
  color: #bdc1ff;
  font-size: 1.5rem;
}

.menu-card .card-report .report .name {
  color: white;
  font-size: 2.4rem;
  font-weight: 300;
}

.menu-card .menu {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  padding: 2.5rem;
}

.menu-card .menu .menu-link {
  color: #6f76c8;
  font-size: 1.8rem;
  cursor: pointer;
}

.menu-card .menu .menu-link:hover {
  color: white;
}

.menu-card .menu .menu-active {
  color: white;
}

.regular-card {
  width: 100%;
  border-radius: 1.6rem;
  background-repeat: no-repeat;
  background-position: 92% -1rem;
}

.regular-card .property-card {
  position: relative;
  background-color: #1c1f4a;
  margin-top: 4rem;
  border-radius: 1.6rem;
  padding: 2.5rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  gap: 0.8rem;
}

.regular-card .property-card:hover {
  background-color: #33387a;
}

.regular-card .property-card .row {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  width: 100%;
}

.regular-card .property-card .row .title {
  color: white;
  font-size: 1.8rem;
  font-weight: 500;
  z-index: 98;
}

.regular-card .property-card .row .points {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.regular-card .property-card .row .points:hover .point {
  background-color: white;
}

.regular-card .property-card .row .points:before {
  content: '';
  background-color: pink;
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  border-radius: 1.6rem;
  display: none;
  z-index: 1;
}

.regular-card .property-card .row .points:hover::before {
  background-color: #1c1f4a;
  display: block;
}

.regular-card .property-card .row .points .point {
  background-color: #bdc1ff;
  width: 0.4rem;
  height: 0.4rem;
  border-radius: 50%;
  margin: 0.2rem;
  z-index: 99;
}

.regular-card .property-card .row-2 {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  width: 100%;
  z-index: 97;
}

.regular-card .property-card .row-2 .hours {
  color: white;
  font-size: 3rem;
  font-weight: 300;
}

.regular-card .property-card .row-2 .description {
  color: #bdc1ff;
  font-size: 1.5rem;
}

.work {
  background-color: #ff8c66;
}

.play {
  background-color: #56c2e6;
}

.study {
  background-color: #ff5c7c;
}

.exercise {
  background-color: #4acf81;
}

.social {
  background-color: #7536d3;
}

.selfcare {
  background-color: #f1c65b;
}
</style>