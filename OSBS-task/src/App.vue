<template>
  <div id="app" class="container-fluid">
    <div class="dropdown">
      <ul>
        <li>
          <img src="./assets/home.png" class="top-right-home" />
        </li>
        <li>
          <img src="./assets/menu .png" onclick="myFunction()" class="top-right-menu" />
          <div id="myDropdown" class="dropdown-content">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
          </div>
        </li>
      </ul>
      <br />
      <br />
      <br />
      <br />
      <p class="float-left">Data Labs</p>

      <p class="p1">The power of Data via</p>
      <p class="p1">Artificial Intelligence and Machine Learning</p>
      <br />
      <br />
      <ul>
        <li>
          <p class="p2">Vision Analytics</p>
        </li>
        <li>
          <p class="p2">Text Analytics</p>
        </li>
        <li>
          <p class="p2">Conversational AI</p>
        </li>
      </ul>
      <p class="p3">Reach Us</p>
      <br />
    </div>
    <br />
    <ul>
      <li>
        <img src="./assets/Layer 50.png" alt />
      </li>&ensp;&ensp;&ensp;&ensp;
      <li>
        <img src="./assets/Layer 53.png" alt />
      </li>&ensp;&ensp;&ensp;&ensp;
      <li>
        <img src="./assets/Layer 51.png" alt />
      </li>&ensp;&ensp;&ensp;&ensp;
      <li>
        <img src="./assets/Layer 52.png" alt />
      </li>
    </ul>
    <div id="div2" class="container-fluid">
      <br />
      <div class="row" id="row">
        <div class="col-6 col-md-4"></div>
        <div id="cell" class="col-12 col-md-8">Vision Analytics</div>
      </div>
      <br />
      <div class="row">
        <div class="col-6 col-md-4">
          <img src="./assets/Layer 36.png" class="img-fluid" alt />
        </div>
        <div class="col-12 col-md-8">
          <span class="p4">
            <p>Train algorithms to detect humans and their actions</p>
            <p>(gestures) for context of many use cases</p>
          </span>
          <br />
          <span class="p5">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia</p>
            <p>deserunt id cumque culpa magni provident saepe nostrum ea laborum,</p>
            <p>sunt odio ratione alias velit ipsa fuga illo! Dolorum, debitis culpa?</p>
          </span>
          <br />
          <button class="button" style="float:left">Learn More ></button>
        </div>
      </div>
      <br />
      <br />
      <div class="row container-fluid">
        <div id="cell1" class="col">
          <div class="row">
            <div class="col-6 col-md-4">
              <br />
              <br />
              <img src="./assets/Layer 5.png" class="img-fluid" />
            </div>
            <div id="is" class="col-12 col-md-8" style="text-align:left">
              <br />
              <br />Industrial Safety
            </div>
          </div>
          <div id="cell" class="col col1">
            <br />The following are our automated solutions aimed at enhancing safety of work place and reduce injuries and accidents.
            <br />
            <button class="button1" style="float:right">Learn More ></button>
          </div>
        </div>
        <div id="cell1" class="col">
          <div class="row">
            <div class="col-6 col-md-4">
              <br />
              <br />
              <img src="./assets/Layer 56.png" class="img-fluid" />
            </div>
            <div id="is" class="col-12 col-md-8" style="text-align:left">
              <br />
              <br />Industrial Safety
            </div>
          </div>
          <div id="cell" class="col col1">
            <br />We have an automated solution that utilizes Vision Intelligence to perform accurate facial recognition of people. Potential use-cases for this facial recognition are
            <br />
            <button class="button1" style="float:right">Learn More ></button>
          </div>
        </div>
        <div id="cell1" class="col">
          <div class="row">
            <div class="col-6 col-md-4">
              <br />
              <br />
              <img src="./assets/Layer 7.png" class="img-fluid" />
            </div>
            <div id="is" class="col-12 col-md-8" style="text-align:left">
              <br />
              <br />Activity Recognition
            </div>
          </div>
          <div id="cell" class="col col1">
            <br />Human activity recognition is an important area of Vision Intelligence. We have developed the following solutions using trained Neural Networks to improve safety and well-being
            <br />
            <button class="button1" style="float:right">Learn More ></button>
          </div>
        </div>
      </div>
      <br />
      <br />
      <br />
    </div>
    <div class="div3 container-fluid" style="background-color:transparent">
      <br />
      <br />
      <h3 class="contact">Contact Us</h3>
      <br />
      <p class="p6">Even the all-powerful Pointing has control the blind texts</p>
      <p class="p6">it is an almost unorthographic life One day</p>
      <br />
      <br />
      <form class="form-group container" id="form">
        <div class="form-row">
          <div class="col">
            <input
              type="text"
              class="form-control"
              placeholder="First name"
              style="background-color:transparent"
            />
          </div>
          <div class="col">
            <input
              type="text"
              class="form-control"
              placeholder="Last name"
              style="background-color:transparent"
            />
          </div>
        </div>
        <br />
        <div>
          <label for="Pick neccesary services" style="float:left">Pick neccesary services</label>
          <br />
          <ul>
            <li>
              <input class="formbutton" type="button" value="Web" />
            </li>
            <li>
              <input class="formbutton" type="button" value="IOS" />
            </li>
            <li>
              <input class="formbutton" type="button" value="Android" />
            </li>
            <li>
              <input class="formbutton" type="button" value="UI/UX Design" />
            </li>
            <li>
              <input class="formbutton" type="button" value="Other" />
            </li>
          </ul>
        </div>
        <div class="form-row">
          <div class="col">
            <input
              type="number"
              class="form-control"
              placeholder="Phone number"
              style="background-color:transparent"
            />
          </div>
          <div class="col">
            <input
              type="email"
              class="form-control"
              placeholder="email"
              style="background-color:transparent"
            />
          </div>
        </div>
        <br />
        <br />
        <div class="form-row">
          <input
            type="text"
            class="form-control"
            placeholder="Message"
            style="background-color:transparent"
          />
        </div>
        <br />
        <br />
        <button type="button" class="btn btn-primary">Send Now</button>
      </form>
      <br />
      <br />
      <br />
      <div class="div4 container-fluid">
        <br />
        <br />
        <br />
        <br />
        <br />
        <ul>
          <li>
            <img src="./assets/clutch.png" alt="clutch" />
          </li>
          <li>
            <img src="./assets/instagram.png" alt="instagram" />
          </li>
          <li>
            <img src="./assets/in.png" alt="LinkedIn" />
          </li>
          <li>
            <img src="./assets/twitter.png" alt="twitter" />
          </li>
          <li>
            <img src="./assets/youtube.png" alt="youtube" />
          </li>
          <li>
            <img src="./assets/facebook.png" alt="facebook" />
          </li>
          <li>
            <img src="./assets/G+.png" alt="Google+" />
          </li>
        </ul>
        <br />
        <br />
        <div class="container AddStyle">
          <div class="row">
            <div class="col-sm">
              <h3>OPTISOL INC.</h3>
              <br />
              <p>9554, N BEXLEY DRIVE,</p>
              <p>STRONGSVILLE,</p>
              <p>OHIO 44136</p>
              <p>+1-415-233-4737</p>
            </div>
            <div class="col-sm">
              <h3>OPTISOL Ireland</h3>
              <br />
              <p>RUBICON CENTRE, CIT CAMPUS,</p>
              <p>BISHOPSTOWN, CORK,</p>
              <p>IRELAND - T12Y275</p>
              <p>+353 (021) 4214593</p>
            </div>
            <div class="col-sm">
              <h3>Middle East</h3>
              <br />
              <p>P.O. BOX 16726, SHEIKH ZAYED ROAD,</p>
              <p>DUBAI, UAE</p>
              <p>+971-55-609-5665</p>
            </div>
          </div>
        </div>
        <br />
        <br />
        <div class="container AddStyle">
          <div class="row">
            <div class="col-sm">
              <h3>INDIA - CHENNAI</h3>
              <br />
              <p>BAID HI TECH PARK, 5TH FLR,</p>
              <p>ECR, THIRUVANMIYUR,</p>
              <p>CHENNAI - 600041</p>
              <p>+91-44-42108070</p>
            </div>
            <div class="col-sm">
              <h3>INDIA - Madurai</h3>
              <br />
              <p>PLOT NO.228, 2ND FLOOR,</p>
              <p>LIG COLONY,</p>
              <p>K.K.NAGAR, MDU - 20</p>
              <p>+91-452-4392350</p>
            </div>
            <div class="col-sm">
              <br />UK: +44-20-3769-0869
              <br />
              <br />SWEDEN: +46-737331349
            </div>
          </div>
        </div>
        <br />
        <br />
        <br />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#div2 {
  background-image: url("./assets/Layer 9.png");
}
#row {
  font-size: 55px;
  line-height: 40px;
  color: #ffffff;
  font-family: "Oswald";
  font-weight: 400;
}
#cell {
  text-align: start;
  -moz-column-fill: balance;
  column-fill: balance;
}
#is {
  font-size: 28px;
  line-height: 29px;
  color: #ffffff;
  font-family: "Ubuntu";
  font-weight: 400;
}
#cell1 {
  box-shadow: 0px 6px 59px rgba(0, 0, 0, 0.7);
  background-image: linear-gradient(0deg, #147bed 0%, #189dec 100%);
  border-radius: 6px;
  background-color: #0000002c;
}
#form {
  font-size: 16px;
  line-height: 24px;
  color: #434343;
  font-family: "George Rounded Light";
  font-weight: 300;
}
h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

.p1 {
  font-size: 40px;
  line-height: 42px;
  color: #ffffff;
  font-family: "Codec Cold Trial";
  font-weight: bold;
  text-align: center;
}
.p2 {
  font-size: 20px;
  line-height: 32px;
  color: #ffffff;
  font-family: "Codec Cold Trial";
  font-weight: 300;
  text-align: center;
}
.p3 {
  border: 2px solid white;
  padding: 6px;
  margin-inline-start: 45%;
  margin-inline-end: 45%;
  font-size: 10px;
  letter-spacing: 1px;
  line-height: 30px;
  color: #ffffff;
  font-family: "George Rounded Light";
  font-weight: 300;
}
.p4 {
  width: 960px;
  height: 173px;
  font-size: 25px;
  letter-spacing: 1px;
  line-height: 26px;
  color: #ffffff;
  font-family: "Ubuntu";
  font-weight: 400;
  font-style: italic;
  text-align-last: left;
  text-align: left;
}
.p5 {
  width: 683px;
  height: 118px;
  font-size: 16px;
  letter-spacing: 0px;
  line-height: 22px;
  color: #ffffff;
  font-family: "Ubuntu";
  font-weight: 400;
  text-align-last: left;
  text-align: left;
}
.p6 {
  font-size: 25px;
  line-height: 30px;
  color: #4f4f4f;
  font-family: "Ubuntu";
  font-weight: 400;
  font-style: italic;
  text-align: center;
}
.contact {
  font-size: 50px;
  line-height: 58px;
  color: #333333;
  font-family: "Oswald";
  font-weight: 400;
}
.dropdown {
  background-image: url("./assets/Layer 44.png");
  background-color: black;
  background-size: auto;
  background-repeat: no-repeat;
}
.div3 {
  background: url("./assets/Layer 100.png") no-repeat;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.div4 {
  background-image: url("./assets/Layer 23.png");
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.dropbtn {
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

.dropbtn:hover,
.dropbtn:focus {
  background-color: #2980b9;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.show {
  display: block;
}
.top-right-home {
  position: absolute;
  top: 10px;
  right: 46px;
}
.top-right-menu {
  position: absolute;
  top: 10px;
  right: 16px;
}
.float-left {
  position: absolute;
  top: 10px;
  left: 60px;
  border: 2px solid rgb(17, 121, 240);
  padding: 3px;
  font-size: 10px;
  color: #ffffff;
  font-weight: 600;
  font-size: 13px;
  letter-spacing: 0px;
  line-height: 18px;
  font-family: "Raleway";
}
.button {
  background-color: rgb(255, 255, 255);
  border: none;
  color: rgb(12, 157, 241);
  padding: 7px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  border-radius: 12px;
}
.button1 {
  background-color: rgb(20, 192, 245);
  border: none;
  color: rgb(255, 255, 255);
  padding: 7px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  border-radius: 12px;
}
.formbutton {
  background-color: rgba(255, 255, 255, 0);
  border: 1px solid rgb(68, 68, 68);
  color: rgb(48, 49, 49);
  padding-left: 40px;
  padding-right: 40px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 8px 8px;
  border-radius: 20px;
}
.col1 {
  width: 447px;
  height: 165px;
  font-size: 13px;
  letter-spacing: 1px;
  line-height: 16px;
  color: #ffffff;
  font-family: "Ubuntu";
  font-weight: 400;
  text-align: start;
}
.AddStyle {
  font-size: 20px;
  letter-spacing: 1px;
  line-height: 19px;
  color: #ffffff;
  font-family: "Bahnschrift";
  text-align: left;
}
</style>
