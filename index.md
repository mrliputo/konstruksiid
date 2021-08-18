<style type="text/css">
   HTML CSSResult Skip Results Iframe
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap");
@media print {
  @page {
    margin: 0;
    size: A4;
  }
  * {
    -webkit-print-color-adjust: exact;
  }
}
* {
  font-family: "Montserrat", sans-serif;
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

body {
  background: #5f6368;
}

.toCenter {
  width: 100%;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.grid-container {
  margin: auto;
  display: grid;
  grid-template-columns: 0.33fr 1fr;
  width: 210mm;
  height: 297mm;
  overflow: hidden;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.7);
}
.grid-container .zone-1 {
  padding: 40px 20px;
  padding-left: 35px;
  background: #d1d1d1;
  width: 100%;
  color: #313131;
}
.grid-container .zone-1 .profile {
  display: inline-flex;
  margin-bottom: 5px;
  margin-left: -15px;
  width: 220px;
  height: 220px;
  border-radius: 50%;
  background-image: url("https://image.freepik.com/free-photo/waist-up-portrait-handsome-serious-unshaven-male-keeps-hands-together-dressed-dark-blue-shirt-has-talk-with-interlocutor-stands-against-white-wall-self-confident-man-freelancer_273609-16320.jpg");
  background-position: center top;
  background-size: 200%;
  border: 4px solid #2c2b29;
}
.grid-container .zone-1 .contact-box {
  margin-top: 10px;
}
.grid-container .zone-1 .contact-box > * {
  width: 100%;
  display: grid;
  grid-template-columns: 0.3fr 1fr;
  margin-top: 25px;
  align-items: center;
}
.grid-container .zone-1 .contact-box > * i {
  font-size: 1.3em;
}
.grid-container .zone-1 .contact-box > * .text {
  display: inline-flex;
  word-break: break-all;
}
.grid-container .zone-1 .personal-box {
  margin-top: 35px;
}
.grid-container .zone-1 .personal-box > *:not(.title) {
  margin: 25px 0px;
  grid-template-columns: 0.55fr 1fr;
  display: grid;
}
.grid-container .zone-1 .personal-box .progress .dot {
  display: inline-block;
  width: 10px;
  height: 10px;
  background-color: #313131;
  border-radius: 50%;
  margin-left: 4px;
}
.grid-container .zone-1 .personal-box .progress .dot.active {
  background-color: #9db858;
}
.grid-container .zone-1 .hobbies-box {
  margin-top: 35px;
}
.grid-container .zone-1 .hobbies-box .logo {
  margin: 10px 0px;
  display: grid;
  grid-template: 1fr 1fr/1fr 1fr;
  font-size: 2.8em;
  grid-row-gap: 15px;
}
.grid-container .zone-2 {
  background: #2c2b29;
  padding: 40px 20px;
  padding-right: 75px;
  color: #b5b5b4;
}
.grid-container .zone-2 .headTitle {
  font-size: 2.1em;
  color: #9db858;
}
.grid-container .zone-2 .headTitle h1 {
  font-weight: 400 !important;
}
.grid-container .zone-2 .subTitle h1 {
  font-weight: 400 !important;
}
.grid-container .zone-2 .box {
  display: inline-block;
  padding: 2px 70px 2px 20px;
  margin-left: -20px;
  margin-top: 35px;
  background: #9db858;
  color: #2c2b29;
}
.grid-container .zone-2 .group-1 .desc {
  margin-top: 15px;
  line-height: 1.5;
}
.grid-container .zone-2 .group-2 .desc {
  margin-top: 15px;
  margin-left: 20px;
}
.grid-container .zone-2 .group-2 .desc ul {
  position: relative;
  margin-top: 20px;
  margin-left: 5px;
}
.grid-container .zone-2 .group-2 .desc ul:before {
  content: "";
  position: absolute;
  top: 12px;
  left: -22px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #9db858;
}
.grid-container .zone-2 .group-2 .desc ul li {
  list-style-type: none;
  position: relative;
}
.grid-container .zone-2 .group-2 .desc ul li:before {
  content: "";
  position: absolute;
  top: 12px;
  left: -18px;
  height: 60px;
  border-left: 2px solid #9db858;
}
.grid-container .zone-2 .group-2 .desc ul:last-of-type li:before {
  content: none;
}
.grid-container .zone-2 .group-2 .desc ul li div:last-of-type {
  color: #9db858;
  font-weight: bold;
}
.grid-container .zone-2 .group-3 .desc {
  margin-top: 15px;
  margin-left: 20px;
}
.grid-container .zone-2 .group-3 .desc ul {
  position: relative;
  margin-top: 20px;
  margin-left: 5px;
}
.grid-container .zone-2 .group-3 .desc ul:before {
  content: "";
  position: absolute;
  top: 30px;
  left: -22px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #9db858;
}
.grid-container .zone-2 .group-3 .desc ul li {
  list-style-type: none;
  position: relative;
}
.grid-container .zone-2 .group-3 .desc ul li:before {
  content: "";
  position: absolute;
  top: 30px;
  left: -18px;
  height: 100px;
  border-left: 2px solid #9db858;
}
.grid-container .zone-2 .group-3 .desc ul:last-of-type li:before {
  content: none;
}
.grid-container .zone-2 .group-3 .desc ul li div:nth-child(2) {
  color: #9db858;
  font-weight: bold;
}
  </style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">

<div class="grid-container">
  <div class="zone-1">
    <div class="toCenter">
      <div class="profile"></div>
    </div>
    <div class="contact-box">
      <div class="title">
        <h2>Contact</h2>
      </div>
      <div class="call"><i class="fas fa-phone-alt"></i>
        <div class="text">(+66) 987654321</div>
      </div>
      <div class="home"><i class="fas fa-home"></i>
        <div class="text">Thailand</div>
      </div>
      <div class="website"><i class="fas fa-globe"></i>
        <div class="text">https://codepen.io/MiniMark</div>
      </div>
      <div class="email"><i class="fas fa-envelope"></i>
        <div class="text">info@gmail.com</div>
      </div>
    </div>
    <div class="personal-box">
      <div class="title">
        <h2>Personal Skills</h2>
      </div>
      <div class="skill-1">
        <p>English</p>
        <div class="progress">
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
        </div>
      </div>
      <div class="skill-2">Spanish<div class="progress">
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot"></div>
          <div class="dot"></div>
          <div class="dot"></div>
        </div>
      </div>
      <div class="skill-3">German<div class="progress">
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot"></div>
          <div class="dot"></div>
          <div class="dot"></div>
          <div class="dot"></div>
        </div>
      </div>
      <div class="skill-4">British<div class="progress">
          <div class="dot active"></div>
          <div class="dot active"></div>
          <div class="dot"></div>
          <div class="dot"></div>
          <div class="dot"></div>
          <div class="dot"></div>
          <div class="dot"></div>
        </div>
      </div>
    </div>
    <div class="hobbies-box">
      <div class="title">
        <h2>Hobbies</h2>
      </div>
      <div class="logo">
        <div class="logo-1"><i class="fas fa-gamepad"></i></div>
        <div class="logo-2"><i class="fas fa-tv"></i></div>
        <div class="logo-3"><i class="fas fa-camera"></i></div>
        <div class="logo-4"><i class="fas fa-lightbulb"></i></div>
      </div>
    </div>
  </div>
  <div class="zone-2">
    <div class="headTitle">
      <h1>Christopher<br><b>Baltimore</b></h1>
    </div>
    <div class="subTitle">
      <h1>Architect<h1>
    </div>
    <div class="group-1">
      <div class="title">
        <div class="box">
          <h2>About Me</h2>
        </div>
      </div>
      <div class="desc">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure deserunt excepturi numquam obcaecati doloribus ab quisquam sapiente quidem officiis aspernatur. A quae totam provident accusamus iure esse earum magnam adipisci, odit libero inventore laborum, rerum laudantium maxime corporis consequatur repellendus.</div>
    </div>
    <div class="group-2">
      <div class="title">
        <div class="box">
          <h2>Education</h2>
        </div>
      </div>
      <div class="desc">
        <ul>
          <li>
            <div class="msg-1">2017-2018 | Lorem, ipsum</div>
            <div class="msg-2">Masterall School of Texas</div>
          </li>
        </ul>
        <ul>
          <li>
            <div class="msg-1">2014-2017 | Lorem, ipsum</div>
            <div class="msg-2">Lorem, ipsum dolor.</div>
          </li>
        </ul>
        <ul>
          <li>
            <div class="msg-1">2012-2014 | Lorem ipsum dolor sit</div>
            <div class="msg-2">Lorem ipsum dolor sit amet.</div>
          </li>
        </ul>
      </div>
    </div>
    <div class="group-3">
      <div class="title">
        <div class="box">
          <h2>Education</h2>
        </div>
      </div>
      <div class="desc">
        <ul>
          <li>
            <div class="msg-1">Present | Achitect</div>
            <div class="msg-2">Lorem, ipsum dolor</div>
            <div class="msg-3">Lorem ipsum dolor sit amet consectetur adipisicing.</div>
          </li>
        </ul>
        <ul>
          <li>
            <div class="msg-1">2019-2020 | Draftsman</div>
            <div class="msg-2">Lorem ipsum dolor sit</div>
            <div class="msg-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
          </li>
        </ul>
        <ul>
          <li>
            <div class="msg-1">2018-2019 | Junior Draftman</div>
            <div class="msg-2">Lorem, ipsum</div>
            <div class="msg-3">Lorem, ipsum dolor sit amet consectetur adipisicing.</div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>
