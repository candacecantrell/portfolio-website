<template>
<div class="mainClass">
    <v-app-bar
      fixed
      color="#6A76AB"
      dark
      shrink-on-scroll
      prominent
      src="../assets/desertRoad.jpg"
      fade-img-on-scroll
      scroll-target="#scrolling-techniques-3"
    >
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          gradient="to top right, rgba(100,115,201,.7), rgba(25,32,72,.7)"
        ></v-img>
      </template>

      <v-toolbar-title>Candace Cantrell Web Developer</v-toolbar-title>

      <v-spacer></v-spacer>

      <template v-slot:extension>
        <v-tabs align-with-title class="menuItems">
          <v-tab><a href="#home">Home</a></v-tab>
          <v-tab><a href="#about">About</a></v-tab>
          <v-tab><a href="#portfolio">Porfolio</a></v-tab>
          <v-tab><a href="#contact">Contact</a></v-tab>
        </v-tabs>
      </template>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-3"
      class="overflow-y-auto"
      max-height="900"
    >
        <div class="aboutClass mx-auto" id="home">
          <div class="timelineClass">
           <v-card
    max-width="375"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/lists/ali.png"
      height="300px"
      dark
    >
      <v-row class="fill-height">
        <v-card-title>

          <v-spacer></v-spacer>
        </v-card-title>

        <v-spacer></v-spacer>

        <v-card-title class="white--text pl-12 pt-12">
          <div class="display-1 pl-12 pt-12" id="about">Candace Cantrell</div>
        </v-card-title>
      </v-row>
    </v-img>

    <v-list two-line>
      <v-list-item >
        <v-list-item-icon>
          <v-icon color="indigo">mdi-phone</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title id="contact">(385) 985-6614</v-list-item-title>
          <v-list-item-subtitle>Mobile</v-list-item-subtitle>
        </v-list-item-content>

        <v-list-item-icon>
          <v-icon>mdi-message-text</v-icon>
        </v-list-item-icon>
      </v-list-item>

      <v-list-item >
        <v-list-item-action></v-list-item-action>
      </v-list-item>

      <v-divider inset></v-divider>

      <v-list-item >
        <v-list-item-icon>
          <v-icon color="indigo">mdi-email</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title>candacecantrell555@gmail.com</v-list-item-title>
          <v-list-item-subtitle>Work</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-list-item >
        <v-list-item-action></v-list-item-action>

        <v-list-item-content>
          <v-list-item-title>Github</v-list-item-title>
          <v-list-item-subtitle class="linkStyle"><a target="blank" href="https://github.com/candacecantrell">https://github.com/candacecantrell <v-icon color="indigo">mdi-open-in-new</v-icon></a></v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider inset></v-divider>

      <v-list-item >
        <v-list-item-icon>
          <v-icon color="indigo">mdi-map-marker</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title>Cedar Hills, UT</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
    </v-list>
  </v-card>
          </div>
          <div class="timelineClass">
   <v-timeline
        align-top
        dense
      >
        <v-timeline-item
          color="indigo lighten-2"
          small
        >
          <v-row class="pt-1">
              <strong>Web Technologies</strong>
          </v-row>
          <v-row>
              <div class="caption">VueJs</div>
          </v-row>
          <v-row>
              <div class="caption">ReactJs</div>
          </v-row>
          <v-row>
              <div class="caption">NodeJs</div>
          </v-row>
          <v-row>
              <div class="caption">VuetifyJs</div>
          </v-row>
          <v-row>
              <div class="caption">Wordpress</div>
          </v-row>
          <v-row>
              <div class="caption">HTML</div>
          </v-row>
          <v-row>
              <div class="caption">CSS</div>
          </v-row>
          <v-row>
              <div class="caption">SASS</div>
          </v-row>
          <v-row>
              <div class="caption">Bootstrap</div>
          </v-row>
          <v-row>
              <div class="caption">Git</div>
          </v-row>
        </v-timeline-item>

        <v-timeline-item
          color="indigo lighten-2"
          small
        >
          <v-row class="pt-1">
              <strong>Coding Languages</strong>
          </v-row>
          <v-row>
              <div class="caption">Javascript</div>
          </v-row>
          <v-row>
              <div class="caption">C#</div>
          </v-row>
          <v-row>
              <div class="caption">Python</div>
          </v-row>
        </v-timeline-item>

        <v-timeline-item
          color="indigo lighten-2"
          small
        >
          <v-row class="pt-1">
              <strong>Design</strong>
          </v-row>
          <v-row>
              <div class="caption">Photoshop</div>
          </v-row>
          <v-row>
              <div class="caption">Illustrator</div>
          </v-row>
          <v-row>
              <div class="caption">InDesign</div>
          </v-row>
        </v-timeline-item>
      </v-timeline>
          </div>
        </div>
          <div class="portfolioClass" id="portfolio">
            <h2 class="display-3 text-center projecth2">Projects</h2>

   <v-tabs centered slider-color="indigo"
  >
    <v-tab class="indigo--text">
      React
    </v-tab>
    <v-tab class="indigo--text">
      Vue
    </v-tab>
              <v-tab-item>
                  <v-hover>
    <template v-slot:default="{ hover }">
      <v-card
        class="mx-auto websiteCard"
      >
        <v-img src="../assets/city-img.jpg"></v-img>

        <v-card-text>
          <ul class="websiteText">
          <h2 class="title primary--text">React: Quinault Motels</h2>
          <li>Website Url: https://app.netlify.com/sites/candace-cantrell-react-hotel/overview</li>
          <li>ReactJs Front End</li>
          <li>NodeJs Server</li>
          </ul>
          
        </v-card-text>

        <v-fade-transition>
          <v-overlay
            v-if="hover"
            absolute
            color="#036358"
          >
          <div class="cardBtn">
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://candace-cantrell-react-hotel.netlify.app">View Site</a></v-btn>
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://github.com/candacecantrell/hotel-app">View Site Code</a></v-btn>
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://github.com/candacecantrell/hotels-node-server">View Server Code</a></v-btn>
            </div>
          </v-overlay>
        </v-fade-transition>
      </v-card>
    </template>
  </v-hover>
                </v-tab-item>
    <v-tab-item>
                        <v-hover>
    <template v-slot:default="{ hover }">
      <v-card
        class="mx-auto websiteCard"
      >
        <v-img src="../assets/city-img.jpg"></v-img>

        <v-card-text>
          <ul class="websiteText">
          <h2 class="title primary--text">Vue: The Audio Shop</h2>
          <li>Website Url: https://candace-cantrell-vue.netlify.app</li>
          <li>VueJs Front End</li>
          <li>Node Server</li>
          <li>GraphQl Server</li>
          <p>*Cassettes for this site will not be displayed undless the Docker container for this site is running. Instructions can be found in the Readme file for the GraphQl server.</p>
          </ul>
          
        </v-card-text>

        <v-fade-transition>
          <v-overlay
            v-if="hover"
            absolute
            color="#036358"
          >
          <div class="cardBtn">
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://candace-cantrell-vue.netlify.app">View Site</a></v-btn>
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://github.com/candacecantrell/dgm4790final-frontend">View Site Code</a></v-btn>
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://github.com/candacecantrell/node-server">View Node Server Code</a></v-btn>
            <v-btn color="indigo lighten-5" small><a target="blank" href="https://github.com/candacecantrell/dgm4790-graphql">View GraphQl Server Code</a></v-btn>
            </div>
          </v-overlay>
        </v-fade-transition>
      </v-card>
    </template>
  </v-hover>
    </v-tab-item>
        </v-tabs>

  <!-- </v-card> -->
  
  </div>
      <v-card height="150">
    <v-footer
      absolute
      class="font-weight-medium"
    >
      <v-col
        class="text-center"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Candace Cantrell</strong>
      </v-col>
    </v-footer>
  </v-card>
   </v-sheet>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
        data: () => ({
      overlay: false,
    }),
  }
</script>
<style scoped>
.mainClass {
  width: 100vw;
}
.aboutClass {
  margin-top: 250px;
  width: 100vw;
}
.menuItems a {
  text-decoration: none;
  color: #FFFFFF;
}
.linkStyle a {
  text-decoration: none;
  color: black;
}
.timelineClass {
  display: flex;
  justify-content: center;
  width: 90vw;
  margin: 40px 5vw 20px 5vw;
}
.skillsList {
  list-style: none;
  line-height: 1.7;
}
.skillsList h2 {
  font-size: 20px;
}
.portfolioClass {
  margin-top: 200px;
}
.cardBtn {
  display: flex;
  flex-direction: column;
}
.cardBtn button {
  margin-bottom: 10px;
}
.cardBtn a {
  text-decoration: none;
}
.websiteCard {
  margin: 50px 0 70px 0;
  max-width: 80%;
}
.websiteText li {
  margin: 9px 0 9px 0;
}
.projecth2 {
  margin-bottom: 30px;
}
@media screen and (min-width: 800px) {
  .aboutClass {
    max-width: 1200px;
    display: flex;
    flex-direction: row;
}

  .timelineClass {
  width: 40%;
  margin: 20px 5vw 20px 5vw;
  display: flex;
  flex-direction: row;
}
.websiteCard {
  max-width: 70%;
}
  }
</style>
