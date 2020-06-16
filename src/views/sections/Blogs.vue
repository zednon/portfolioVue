<template>
  <div class="wrapper">
    <div class="section section-blogs-1">
      <!-- Blogs 1 -->
      <div class="container">
        <div class="md-layout">
          <div class="md-layout-item md-size-80 md-small-size-100 mx-auto">
            <h2 class="title">
            Highlighted Projects
            </h2>
            <br>
            <blog-card
              card-plain
              type="horizontal"
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost.cardBlogPost1"
            >
              <template slot="cardContent">
                <h6 class="card-category text-success">
                   <md-icon class="text-success">
                    format_shapes
                  </md-icon>
                  UX 
                </h6>
                <h3 class="card-title">
                Protype of User Interface
                </h3>
                <p class="card-description">
        This project was to improve a empoyees work experince using a interface to track pto hours. 
                  <a href="https://agondring.myportfolio.com/"> View my last work here </a>
                </p>
                <p class="author">
                this was made with Adobe XD 
                </p>
              </template>
            </blog-card>
            <blog-card
              card-plain
              type="horizontal"
              reverse-row
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost.cardBlogPost2"
            >
              <template slot="cardContent">
                <h6 class="card-category text-warning">
                  <md-icon class="text-warning">
                    developer_board
                  </md-icon> Front-End
                </h6>
                <h3 class="card-title">
                  <a
                    href="https://zednon.github.io/clickMe/"
                  >A Memery Click Game</a>
                </h3>
                <p class="card-description">
                  Here is a great little react project, using CSS, HTML, and React.
                  <a href="https://github.com/zednon/clickMe"> See the Code </a>
                </p>
                <p class="author">
                  by
                  <a href="javascript:void(0)"> View more Front-End Projects</a>, 2 days
                  ago
                </p>
              </template>
            </blog-card>
          </div>
        </div>
      </div>
      <!-- End Blogs 1 
    </div>
    <div class="section section-blogs-2">
      Blogs 2 
      <div class="container">
        <div class="md-layout">
          <div class="md-layout-item md-size-80 md-small-size-100 mx-auto">
            <h2 class="title">
              Latest Blogposts 2
            </h2>
            <br>
            <div class="md-layout">
              <div class="md-layout-item md-size-33 md-small-size-100">
                <blog-card
                  card-plain
                  :shadow-normal="false"
                  :no-colored-shadow="false"
                  :card-image="cardBlogPost.cardBlogPost1"
                >
                  <template slot="cardContent">
                    <h6 class="card-category text-info">
                      Enterprise
                    </h6>
                    <h4 class="card-title">
                      <a
                        href="javascript:void(0)"
                      >Autodesk looks to future of 3D printing with Project
                        Escher</a>
                    </h4>
                    <p class="card-description">
                      Like so many organizations these days, Autodesk is a
                      company in transition. It was until recently a traditional
                      boxed software company selling licenses.
                      <a href="javascript:void(0)"> Read More </a>
                    </p>
                  </template>
                </blog-card>
              </div>
              <div class="md-layout-item md-size-33 md-small-size-100">
                <blog-card
                  card-plain
                  :shadow-normal="false"
                  :no-colored-shadow="false"
                  :card-image="cardBlogPost2.cardBlogPost1"
                >
                  <template slot="cardContent">
                    <h6 class="card-category text-success">
                      Startups
                    </h6>
                    <h4 class="card-title">
                      <a
                        href="javascript:void(0)"
                      >Lyft launching cross-platform service this week</a>
                    </h4>
                    <p class="card-description">
                      Like so many organizations these days, Autodesk is a
                      company in transition. It was until recently a traditional
                      boxed software company selling licenses.
                      <a href="javascript:void(0)"> Read More </a>
                    </p>
                  </template>
                </blog-card>
              </div>
              <div class="md-layout-item md-size-33 md-small-size-100">
                <blog-card
                  card-plain
                  :shadow-normal="false"
                  :no-colored-shadow="false"
                  :card-image="cardBlogPost2.cardBlogPost2"
                >
                  <template slot="cardContent">
                    <h6 class="card-category text-danger">
                      <md-icon class="text-danger">
                        trending_up
                      </md-icon>
                      Enterprise
                    </h6>
                    <h4 class="card-title">
                      <a
                        href="javascript:void(0)"
                      >6 insights into the French Fashion landscape</a>
                    </h4>
                    <p class="card-description">
                      Like so many organizations these days, Autodesk is a
                      company in transition. It was until recently a traditional
                      boxed software company selling licenses.
                      <a href="javascript:void(0)"> Read More </a>
                    </p>
                  </template>
                </blog-card>
              </div>
            </div>
          </div>
        </div>
      </div>
       End Blogs 2
    </div> 
    <div class="section section-blogs-3">
       Blogs 3 
      <div class="container">
        <div class="md-layout">
          <div class="md-layout-item md-size-80 md-small-size-100 mx-auto">
            <h2 class="title">
              Latest Blogposts 3
            </h2>
            <br>
            <blog-card
              card-plain
              type="horizontal"
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost.cardBlogPost1"
            >
              <template slot="cardContent">
                <h6 class="card-category text-info">
                  Enterprise
                </h6>
                <h3 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Autodesk looks to future of 3D printing with Project
                    Escher</a>
                </h3>
                <p class="card-description">
                  Like so many organizations these days, Autodesk is a company
                  in transition. It was until recently a traditional boxed
                  software company selling licenses. Today, it’s moving to a
                  subscription model. Yet its own business model disruption is
                  only part of the story — and…
                  <a href="javascript:void(0)"> Read More </a>
                </p>
                <p class="author">
                  by
                  <a href="javascript:void(0)"> <b>Mike Butcher</b> </a>, 2 days
                  ago
                </p>
              </template>
            </blog-card>
            <blog-card
              card-plain
              type="horizontal"
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost.cardBlogPost2"
            >
              <template slot="cardContent">
                <h6 class="card-category text-danger">
                  <md-icon class="text-danger">
                    trending_up
                  </md-icon> Trending
                </h6>
                <h3 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >6 insights into the French Fashion landscape</a>
                </h3>
                <p class="card-description">
                  Like so many organizations these days, Autodesk is a company
                  in transition. It was until recently a traditional boxed
                  software company selling licenses. Today, it’s moving to a
                  subscription model. Yet its own business model disruption is
                  only part of the story — and…
                  <a href="javascript:void(0)"> Read More </a>
                </p>
                <p class="author">
                  by
                  <a href="javascript:void(0)"> <b>Mike Butcher</b> </a>, 2 days
                  ago
                </p>
              </template>
            </blog-card>
            <blog-card
              card-plain
              type="horizontal"
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost3.cardBlogPost1"
            >
              <template slot="cardContent">
                <h6 class="card-category text-success">
                  Startups
                </h6>
                <h3 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Lyft launching cross-platform service this week</a>
                </h3>
                <p class="card-description">
                  Like so many organizations these days, Autodesk is a company
                  in transition. It was until recently a traditional boxed
                  software company selling licenses. Today, it’s moving to a
                  subscription model. Yet its own business model disruption is
                  only part of the story — and…
                  <a href="javascript:void(0)"> Read More </a>
                </p>
                <p class="author">
                  by
                  <a href="javascript:void(0)"> <b>Megan Rose</b> </a>, 2 days
                  ago
                </p>
              </template>
            </blog-card>
          </div>
        </div>
      </div>
       End Blogs 3 
    </div>
    <div class="section section-blogs-4">
       Blogs 4 
      <div class="container">
        <div class="md-layout">
          <div class="md-layout-item md-size-66 md-small-size-100 mx-auto">
            <h2 class="title">
              Latest Blogposts 4
            </h2>
            <br>
            <blog-card
              card-plain
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost4.cardBlogPost1"
            >
              <template slot="cardContent">
                <h6 class="card-category text-info">
                  Fashion
                </h6>
                <h3 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >Autodesk looks to future of 3D</a>
                </h3>
                <h5 class="card-description">
                  Don't be scared of the truth because we need to restart the
                  human foundation in truth And I love you like Kanye loves
                  Kanye I love Rick Owens’ bed design but the back is too high
                  for the beams and angle of the ceiling I also wanted to point
                  out that it’s the first album to go number 1 off of
                  streaming...
                </h5>
                <md-button
                  href="javascript:void(0)"
                  class="md-primary md-round"
                >
                  Read more
                </md-button>
              </template>
            </blog-card>
            <blog-card
              card-plain
              :shadow-normal="false"
              :no-colored-shadow="false"
              :card-image="cardBlogPost4.cardBlogPost2"
            >
              <template slot="cardContent">
                <h6 class="card-category text-success">
                  Lifestyle
                </h6>
                <h3 class="card-title">
                  <a
                    href="javascript:void(0)"
                  >We will breathe clean air and exercise</a>
                </h3>
                <h5 class="card-description">
                  Don't be scared of the truth because we need to restart the
                  human foundation in truth And I love you like Kanye loves
                  Kanye I love Rick Owens’ bed design but the back is too high
                  for the beams and angle of the ceiling I also wanted to point
                  out that it’s the first album to go number 1 off of
                  streaming...
                </h5>
                <md-button
                  href="javascript:void(0)"
                  class="md-primary md-round"
                >
                  Read more
                </md-button>
              </template>
            </blog-card>
          </div>
        </div>
      </div> 
      End Blogs 4 -->
    </div>
  </div>
</template>

<script>
import { BlogCard } from "@/components";
export default {
  name: "Blogs",
  components: {
    BlogCard
  },
  data() {
    return {
      cardBlogPost: {
        cardBlogPost1: require("@/assets/img/project_demo.png"),
        cardBlogPost2: require("@/assets/img/click_me .png")
      },
      // cardBlogPost2: {
      //   cardBlogPost1: require("@/assets/img/examples/blog5.jpg"),
      //   cardBlogPost2: require("@/assets/img/examples/blog7.jpg")
      // },
      // cardBlogPost3: {
      //   cardBlogPost1: require("@/assets/img/examples/blog8.jpg")
      // },
      // cardBlogPost4: {
      //   cardBlogPost1: require("@/assets/img/bg5.jpg"),
      //   cardBlogPost2: require("@/assets/img/examples/blog6.jpg")
      // }
    };
  }
};
</script>

<style lang="scss"></style>
