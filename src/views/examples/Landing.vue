<template>
  <div class="wrapper">
    <parallax
      class="section page-header header-filter"
      parallax-active="true"
      :style="headerStyle"
    >
      <div class="container">
        <div class="md-layout">
          <div class="md-layout-item md-size-50 md-small-size-100">
            <div id="fixtitle">
            <h1 class="title">
            Anna Gondring's Portfolio
            </h1>
            <hr>

            <h2> About Me </h2>
            <p>
             As a child Build GeoCities pages with my friends after school and use them to store extra data. When I went to College I major in History and minor in American Sign. Following College I go a job as a Job Coach for Disabled. I started to realize as much as a positive impact I was having I wanted to solve problems. I started to do Free Code Camp, Code Academy, and Team Tree House. After I felt I had a good understand of the basics I enrolled in a Boot Camp at Columbia University.
           </p>
            </div>
            <br>
  
          </div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section">
        <div class="container">
          <div class="md-layout">
            <div
              class="md-layout-item md-size-66 md-small-size-100 mx-auto text-center"
            >
              <h2 class="title text-center">
             Areas of Focus
              </h2>
              <h5 class="description">
                Lanauges, Skills, Liberies I know
              </h5>
            </div>
          </div>
          <div class="features text-center">
            <div class="md-layout">
              <div class="md-layout-item md-size-33 md-small-size-100">
                <div class="info">
                  <div class="icon developer_board">
                    <md-icon style= "color: blue;" >developer_board</md-icon>
                  </div>
                  <h4 class="info-title">
                    Front-End Engingering 
                  </h4>
                     <h6>See My Projects</h6>
                  <p>
                 I know Javascript, Bootstrap, HTML, CSS, Vue, Jquerry, Node, Express, FireBase, Node.Red, Java 
                  </p>
               
                </div>
              </div>
              <div class="md-layout-item md-size-33 md-small-size-100">
                <div class="info">
                  <div class="icon format_shapes">
                    <md-icon style= "color: green;">format_shapes</md-icon>
                  </div>
                  <h4 class="info-title">
                    UI/UX ADA-UX
                  </h4>
                        <h6>See My Projects</h6>
                  <p>
                 From Wire Frames, to Mock-ups, and ADA Assabliety I am able to provide skills in evverything. 
                 I know Abobe Xd and Aria, I am up to date on WCAG AA and AAA standers.
                  </p>
                </div>
              </div>
              <div class="md-layout-item md-size-33 md-small-size-100">
                <div class="info">
                  <div class="icon smartphone">
                    <md-icon style="color:red;">smartphone</md-icon>
                  </div>
                  <h4 class="info-title">
                    Moble Development
                  </h4>
                        <h6>See My Projects</h6>
                  <p>
                  I am skilled in Fluter, Dart, and Java I can make apps for both Andriod and IOS
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section text-center">
        <div class="container">
          <h2 class="title">
            Work and Education 
          </h2>
          <div class="team">
          
          <div class="md-layout">
          <div
            class="md-layout-item md-size-25 md-small-size-100"
          >
              <rotating-card card-bg="info">
              <template slot="frontRotateCardContent">
              
               <h6 
               class="card-description">2019-2020</h6>
                <h5 class="card-category card-category-social">
                Harlem Edution Center
                </h5>

                <h4 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >STEM Program Manger</a>
                </h4>
                <p class="card-description">
                 Developed a after school program for low income middle school kids in harlem. </p>
              <br>
              <br>
              </template>
              <template slot="backRotateCardContent">
                <h5 class="card-title">
                  Tools and Launages Used:
                </h5>
                <ul class="card-description">
                  <li>
                   Rasibery PI
                  </li>
                                    <li>
                   NODE.RED
                  </li>
                  <li>
                  3D Printing
                  </li>
                 <li>
                  UX/UI design
                  </li>
                 <li>
                  Python
                  </li>
                 <li>
                  Robotics
                  </li>
                </ul>
          
              </template>
            </rotating-card>
          </div>         

            <div
            class="md-layout-item md-size-25 md-small-size-100"
          >
              <rotating-card card-bg="rose">
              <template slot="frontRotateCardContent">
               
               <h6 
               class="card-description">2019</h6>
                <h5 class="card-category card-category-social">
                TeamTreeHouse
                </h5>

                <h4 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >UI/UX</a>
                </h4>
                <p class="card-description">
               I took many classes on UX/UI and finished there corse work for UX developer </p>
              <br>
              <br>
              <br>
              </template>
              <template slot="backRotateCardContent">
                <h5 class="card-title">
                  Tools Used and Developed Skills:
                </h5>
                <ul class="card-description">
                  <li>
                   Abobe XD
                  </li>
                                    <li>
                   Wire Framing
                  </li>
                  <li>
                  Mock-ups
                  </li>
                 <li>
                 User Resurch
                  </li>
                 <li>
                 Paper Wire Framing
                  </li>
                 <li>
                  Finge
                  </li>
                </ul>
          
              </template>
            </rotating-card>
         
      
     
           </div>
          
            <div
            class="md-layout-item md-size-25 md-small-size-100"
          >
              <rotating-card card-bg="info">
              <template slot="frontRotateCardContent">
                 <h6 
               class="card-description">2018-2019</h6>
                <h5 class="card-category card-category-social">
TGTSNBN                </h5>

                <h4 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Web Developer</a>
                </h4>
                <p class="card-description">
               Developed a Website for a 4,000 person meetup group </p>
              <br>
              <br> <br>
              <br>
              </template>
              <template slot="backRotateCardContent">
                <h5 class="card-title">
                  Tools and Launages Used:
                </h5>
                <ul class="card-description">
<br>
                                    <li>
                   Node
                  </li>
                  <li>
                  Vue
                  </li>
                 <li>
                  UX/UI design
                  </li>
                 <li>
                  Express
                  </li>
                 <li>
                  Aria
                  </li>
                </ul>
          
              </template>
            </rotating-card>
          </div>         

            <div
            class="md-layout-item md-size-25 md-small-size-100"
          >
              <rotating-card card-bg="rose">
              <template slot="frontRotateCardContent">
                   <h6 
               class="card-description">2019-2020</h6>
                <h5 class="card-category card-category-social">
                Freelance
                </h5>

                <h4 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Front End Engineer</a>
                </h4>
                <p class="card-description">
             Worked on a few Freelance Projects </p>
              <br>
              <br><br>
              <br>
              </template>
              <template slot="backRotateCardContent">
                <h5 class="card-title">
                  Tools Used and Developed Skills:
                </h5>
                <ul class="card-description">
                  <li>
                  Mock up of a website
                  </li>
                                    <li>
                   User Resurch
                  </li>
                  <li>
                  QA testing
                  </li>
                 <li>
                 Mock up for a site
                  </li>
                 <li>
                 ADA testing 
                  </li>
                  <br>
                </ul>
          
              </template>
            </rotating-card>
           </div>       
          
          
            <div
            class="md-layout-item md-size-25 md-small-size-100"
          >
              <rotating-card card-bg="rose">
              <template slot="frontRotateCardContent">
                   <h6 
               class="card-description">2018-2019</h6>
                <h5 class="card-category card-category-social">
                Columbia University
                </h5>

                <h4 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Full Stack Enginner </a>
                </h4>
                <p class="card-description">
                I attended Columbia University, and took a Full Stack Engineering 6 mounth course      </p>
              <br>
              <br>
              <br>
              </template>
              <template slot="backRotateCardContent">
                <h5 class="card-title">
                  Launages and Libreries Learned:
                </h5>
                <ul class="card-description">
                  <li>
                   Javascript
                  </li>
                                    <li>
                   Node
                  </li>
                  <li>
                  FireBase
                  </li>
                 <li>
                 Api Calls
                  </li>
                 <li>
                   MongoDB
                  </li>
                 <li>
                  Express
                  </li>
                </ul>
          
              </template>
            </rotating-card>
         
      
     
           </div>
                    <div
            class="md-layout-item md-size-25 md-small-size-100"
          >
              <rotating-card card-bg="info">
              <template slot="frontRotateCardContent">
                   <h6 
               class="card-description">2018</h6>
                <h5 class="card-category card-category-social">
FreeCoderCamp               </h5>

                <h4 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Frot End </a>
                </h4>
                <p class="card-description">
             Complected 300 hours of Front End programing</p>
              <br>
              <br> <br>
              <br>
              </template>
              <template slot="backRotateCardContent">
                <h5 class="card-title">
                  Skills Learned:
                </h5>
                <ul class="card-description">
                     <li>
                   HTML
                  </li>
                                    <li>
                   CSS
                  </li>
                  <li>
                  JavaScript
                  </li>
                 <li>
                  Respive Web Design
                  </li>
                 <li>
                  Alt Tags
                  </li>
                 <li>
                  Bootstrap
                  </li>
                </ul>
          
              </template>
            </rotating-card>
          </div>   
         
           </div>




          </div>
        </div>
      </div>
      <div class="section section-contacts">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-small-size-100 mx-auto">
              <h2 class="text-center title">
               Contact Me 
              </h2>
              <h4 class="text-center description">
            Feel free to reach out please
              </h4>
              <form class="contact-form">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50 md-small-size-100">
                    <md-field>
                      <label>Your Name</label>
                      <md-input
                        v-model="name"
                        type="text"
                      />
                    </md-field>
                  </div>
                  <div class="md-layout-item md-size-50 md-small-size-100">
                    <md-field>
                      <label>Your Email</label>
                      <md-input
                        v-model="email"
                        type="email"
                      />
                    </md-field>
                  </div>
                </div>
                <md-field maxlength="5">
                  <label>Your Message</label>
                  <md-textarea v-model="message" />
                </md-field>
                <div class="md-layout">
                  <div
                    class="md-layout-item md-size-33 md-small-size-100 mx-auto text-center"
                  >
                    <md-button class="md-success">
                      Send Message
                    </md-button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import Mixins from "@/plugins/basicMixins";
import {
  BlogCard,

  PricingCard,
  RotatingCard,
  FullBgCard
} from "@/components";

export default {
  components: {
    
    RotatingCard
  },
  mixins: [Mixins.HeaderImage],
  bodyClass: "landing-page",
    props: {
    sectionCardPlain: Boolean,
    sectionMorphingCards: Boolean
  },
  data() {
    return {
       manualRotateState: false,
      manualRotateState2: false,
      manualRotateState3: false,
      image: require("@/assets/img/computer.jpg"),
      name: null,
      email: null,
      message: null,
     
    
   cardRotating: {
        cardRotatingBg1: require("@/assets/img/examples/card-blog5.jpg"),
        cardRotatingBg2: require("@/assets/img/examples/card-blog6.jpg")
      },
    };
  }
};
</script>

<style lang="scss" scoped>
.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}


</style>
