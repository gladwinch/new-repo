<template>
<div class="ct-back-color container-401" style="max-width: 100%">
  <v-container class="ct-container pt-10 hidden-md-and-down">

    <v-avatar height="120" width="120" class="ct-avatar hidden-sm-and-down">
      <img src="../assets/femalepic.png" alt="image" >
    </v-avatar>
    <div class="d-flex justify-space-between white ct-border-radius header-part mb-2">
        
        <div class="d-flex flex-column inner_container-4 align-start justify-space-around">
            <div>
                <v-list-item-title class="mt-2 font-weight-bold ct-primary--text ml-md-8 ml-sm-2">
                    <span class="user-name ct-secondary--text mr-md-6 mr-sm-2 title font-weight-bold">Carla Pipin Ranga</span>
                </v-list-item-title>
                

                <p class="body-2 font-weight-thin grey--text ml-md-8 ml-sm-2">
                    Web Ui/Ux Designer, Graphiс Designer 
                </p>
            </div>

            <div class="mb-3">
                <v-btn class="ct-border-radius text-capitalize font-weight-thin hidden-sm-and-down ml-md-8" color="ct-primary" depressed>
                    <v-icon size="16" color="white">mdi-email</v-icon>
                    <span size="16" class="ml-2 font-weight-thin white--text">Send Message</span>
                </v-btn>

                <v-btn fab dark small color="ct-primary font-weight-thin hidden-sm-and-down ml-4"  :elevation=0>
                    <img src="../assets/play.png" alt="download-icon" class="ct-icon-download" >
                </v-btn>

                <v-btn fab dark small color="ct-primary font-weight-thin hidden-sm-and-down ml-4"  :elevation=0>
                    <img src="../assets/headphone.png" alt="download-icon" class="ct-icon-download" >
                </v-btn>  
            </div>
        </div>

        <div class="d-flex flex-column inner_container align-center justify-space-around pt-3">
            <div class="d-flex hidden-md-and-up">
                <div v-for="n in 5" :key="n" 
                  class="d-flex justify-center ct-secondary align-center sm-icon-container mr-4">
                  <img :src="getImgUrlSm(n)" alt="img" class="ct-icon-img" >
                </div>
            </div>
              
            <div class="text-center mt-2">
                <div class="ct-secondary--text body-1 font-weight-bold">
                  About
                </div>
                <p class="ct-small-text  grey--text font-weight-regular">
                  I'm Conor, I'm a product manager from London. I'm currently looking for new permanent job.
                </p>
            </div>
        </div>

        <div class="d-flex flex-column inner_container-right align-center justify-center">
            <div class="d-flex justify-space-between">

              <div class="d-flex flex-column justify-center">
                <div class="ct-thin-text text-center font-weight-thin">
                  Hourly rate
                </div>

                <div class="ct-price text-center font-weight-bold ct-secondary--text">
                  $ 25 USD
                </div>                
              </div>

              <div class="divide-line mx-2 mt-3"></div>

              <div class="d-flex flex-column justify-center text">
                <div class="ct-thin-text text-center font-weight-thin">
                  Available for 
                </div>

                <div class="ct-price text-center font-weight-bold  ct-secondary--text">
                  8 hours
                </div>                
              </div>

            </div>

            <v-btn class="mt-5 ct-primary 
              font-weight-thin white--text 
              text-capitalize px-12" large rounded :elevation=0>Hire me</v-btn>
            
        </div>
    </div>
  </v-container>
 
  <!-- small screen header -->
  <v-container class="ct-container mt-4 pl-6">
    <v-avatar height="70" width="70" class="ct-avatar-small hidden-lg-and-up">
      <img src="../assets/femalepic.png" alt="image" >
    </v-avatar>

    <v-card class="white py-4 hidden-lg-and-up ct-b-small-box" :elevation=0>
    <div class="d-flex justify-space-between px-6">
      <div>
          <v-list-item-title class="font-weight-bold ct-primary--text ml-10">
              <span class="user-name ct-secondary--text mr-md-6 mr-sm-2 headline font-weight-bold">Carla Pipin</span>
          </v-list-item-title>
          

          <p class="body-2 font-weight-thin grey--text ml-10">
              Web Ui/Ux Designer, Graphiс Designer 
          </p>

          <v-btn class="ct-border-radius text-capitalize font-weight-thin ml-10" color="ct-primary" depressed>
            <v-icon size="16" color="white">mdi-email</v-icon>
            <span size="16" class="ml-2 font-weight-thin white--text">Send Message</span>
          </v-btn>
      </div>

      <div class="d-flex">
        <v-btn fab dark small color="ct-primary font-weight-thin" class="mr-sm-4 mr-sm-4 mr-2"  :elevation=0>
            <img src="../assets/play.png" alt="download-icon" class="ct-icon-download" >
        </v-btn>

        <v-btn fab dark small color="transparent"   :elevation=0>
            <img src="../assets/headphone.png" alt="download-icon" class="ct-icon-download" >
        </v-btn> 
      </div>
    </div>
    </v-card>

   </v-container>
   
   <v-container class="mb-5 hidden-lg-and-up">
   
    <v-card color="transparent" :elevation=0 class="hidden-lg-and-up mt-10">
      <div class="d-flex justify-center hidden-md-and-up">
          <div v-for="n in 5" :key="n" 
            class="d-flex justify-center ct-secondary align-center sm-icon-container-22"
            :class="[n == 5 ? '' : 'mr-4']">
            <img :src="getImgUrlSm(n)" alt="img" class="ct-icon-img-22" >
          </div>
      </div>
    </v-card>

    <v-card color="transparent" :elevation=0 class="hidden-lg-and-up mt-5">
      <div class="text-center mt-2">
          <div class="ct-secondary--text body-1 font-weight-bold">
            About
          </div>
          <p class="ct-small-text  grey--text font-weight-regular">
            I'm Conor, I'm a product manager from London. I'm currently looking for new permanent job.
          </p>
      </div>
    </v-card>

    <v-card class="white pa-6 hidden-lg-and-up ct-b-small-box-22 mt-6" :elevation=0>
      <div class="d-flex justify-space-between">


          <div class="d-flex flex-column justify-center">
            <div class="body-2 text-center font-weight-thin">
              Hourly rate
            </div>

            <div class="ct-price text-center font-weight-bold ct-secondary--text">
              $ 25 USD 
            </div>                
          </div>

          <v-divider
            inset
            vertical
          ></v-divider>

          <div class="d-flex flex-column justify-center text">
            <div class="body-2 text-center font-weight-thin">
              Available for 
            </div>

            <div class="ct-price text-center font-weight-bold  ct-secondary--text">
              8 hours
            </div>                
          </div>

          <v-btn class="ct-primary mt-1 ml-1
              font-weight-thin white--text 
              text-capitalize px-auto px-md-12 px-sm-12" rounded :elevation=0>Hire me</v-btn>

        </div>
    </v-card>

  </v-container>


<!-- Small screen social media icons -->
 
  <!-- <v-container class="d-flex pl-4 mb-10 hidden-md-and-up">
    <div v-for="n in 6" :key="n" 
      class="d-flex justify-center align-center sm-icon-container pa-4 mr-4">
      <img :src="getImgUrlSm(n)" alt="img" class="ct-icon-img" >
    </div>
  </v-container> -->

  <!-- Tab start -->
  <div class="mb-8" style="max-width: 100vw">
    <v-container class="hidden-sm-and-down">
        <v-tabs 
        background-color="transparent" 
        center-active 
        hide-slider 
        height="38"
        class="ct-transform font-weight-light" >
        <v-tab 
            v-for="tab in tabs" 
            :key="tab.id"
            v-on:click="activeTab = tab.title"
            :class="[activeTab == tab.title ? 
            'ct-active': '',
            'nav-tab ct-dark-text mr-2 px-6 font-weight-regular']"
        >{{ tab.title }}</v-tab>
        </v-tabs>
    </v-container>
    
    <v-tabs 
        class="hidden-md-and-up ct-transform" 
        background-color="transparent" 
        center-active 
        hide-slider height="38">
        <v-tab 
        v-for="tab in tabs" 
        :key="tab.id"
        v-on:click="activeTab = tab.title"
        :class="[activeTab == tab.title ? 
            'ct-active': 
            '', 'nav-tab ct-dark-text  font-weight-regular ct-sm']"
        >{{ tab.title }}</v-tab>
    </v-tabs>
  </div>

  <!-- Tab end -->
  
  <!-- Tab Component start -->

<!-- Portfolio -->

  <v-container v-if="activeTab == 'Portfolio'" class="px-2">
    <v-row>
      <v-col
        v-for="image in images"
        :key="image.id"
        cols="12"
        md="4"
        sm="6"
      >
      <div class="d-flex justify-center">
        <img :src="getImgUrl(image.id)" class="ct-image mb-5 mx-auto">
      </div>

      </v-col>
    </v-row>
  </v-container>

  <!-- Work -->
  <v-container v-if="activeTab == 'Work'">
    <v-row>
      <v-col
        v-for="n in 6"
        :key="n"
        cols="12"
        md="6"
        sm="12"
        :class="[n % 2 != 0 ? 'mr-auto' : '', 'work-tile mb-6']"
      >
        <v-card flat class="pa-6 rounde_me">
            <div class="headline ct-secondary--text font-weight-bold">Google</div>

            <div class="d-flex justify-space-between">
                <p class="ct-body-text font-weight-thin grey--text">
                    User interface designer
                </p>

                <p class="ct-body-text font-weight-thin grey--text">
                    Dec 19 - Present 
                </p>
            </div>

            <p class="ct-body-text text-content">I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
        </v-card>       
      </v-col>
    </v-row>
  </v-container>

  <!-- Education -->
  <v-container v-if="activeTab == 'Education'">
    <v-row >
      <v-col
        v-for="n in 6"
        :key="n"
        cols="12"
        sm="12"
        md="6"
        :class="[n % 2 != 0 ? 'mr-auto' : '', 'work-tile mb-6']"
        
      >
        
        <v-card flat class="pa-6 rounde_me">
            <div class="title ct-secondary--text font-weight-bold">California Institute of Technology</div>
            <div class="d-flex justify-space-between">
                <p class="ct-body-text font-weight-thin dark--text">
                    M.Sc in HCI,  Dec 19 - Present
                </p>
                <p class="ct-body-text font-weight-thin dark--text">
                    University
                </p>
            </div>
            <p class="ct-body-text text-content">I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
        </v-card>
      </v-col>
    </v-row>
  </v-container>

  <!-- Skills -->
  <v-container v-if="activeTab == 'Skills'">
    <v-card
      max-width="500"
      class="mx-auto"
      flat
    >
      <v-list class="ct-back-color">
        <v-list-item
          v-for="skill in skills"
          :key="skill.id"
          class="mb-5 pa-2 px-4 ct-box align-center"
        >
          <v-list-item-icon>
            <v-list-item-title v-text="skill.skill" class="ct-width ct-secondary--text pt-1"></v-list-item-title>
          </v-list-item-icon>

          <v-list-item-content>
            <v-progress-linear
              rounded
              height="7"
              v-model="skill.progress"
              color="#956BE3"
            ></v-progress-linear>
          </v-list-item-content>

          <v-list-item-avatar class="ct-secondary--text">
            {{ skill.progress }}%
          </v-list-item-avatar>
        </v-list-item>
      </v-list>
    </v-card>
  </v-container>

</div>
</template>

<script>
  export default {
    name: 'Theme',

    data: () => ({
        value: true,
        activeTab: "Portfolio",
        tabs: [
            { id: 2, title: 'Portfolio' },
            { id: 3, title: 'Work' },
            { id: 4, title: 'Education' },
            { id: 5, title: 'Skills' }
        ],
        data: 'About Section',
        description: "I'm Conor, I'm a product manager from London. I'm currently looking for new permanent job opportunities within London area that will allow my career to develop...I'm Conor, I'm a product manager from London. I'm currently looking for new permanent job opportunities within London area that will allow my career to develop...I'm Conor, I'm a product manager from London. I'm currently looking for new permanent job opportunities within London area that will allow my career to develop...  I'm Conor, I'm a product manager from London. I'm currently looking for new permanent job opportunities within London area that will allow my career to develop...",
        images: [
            { id: 1 },
            { id: 2 },
            { id: 3 },
            { id: 4 },
            { id: 5 }
        ],
        skills: [
            { id: 1, skill: 'Photoshop', progress: 54 },
            { id: 2, skill: 'Illustrator', progress: 84 },
            { id: 3, skill: 'Figma', progress: 90 },
            { id: 4, skill: 'Adobe XD', progress: 65 }
        ]
    }),

    computed: {
        fontSize() {
            switch (this.$vuetify.breakpoint.name) {
            case 'xs': return '3em';
            default: return '4em';
            }
        }
    },

    methods: {
        getImgUrl(id) {
           let image = require.context('../assets/portfolio', false, /\.png$/)
           return image('./' + id + ".png")
        },
        getImgUrlSm(id) {
           let image = require.context('../assets/sm-icons', false, /\.png$/)
           return image('./' + id + ".png")
        },
    }
  }
</script>

<style scoped>
/* Global style */
body {
  font-family: 'Montserrat';
  line-height: 17px;
}

/* Header style */

.ct-primary { background-color: #956BE3!important }
.ct-secondary { background-color: #f6f6f6!important }
.ct-primary--text { color: #f6f6f6 }
.ct-secondary--text { color: #956BE3 }

.ct-back-color { background-color: #E5E5E5!important }
.ct-dark-text { color: #CBCBCB !important }

.container-401 {
  overflow: hidden;
}

.ct-height-container {
  height: 100vh;
}

.ct-border-radius {
    border-radius: 2rem !important;
}

.user-name {
    font-size: 1.8rem !important;
    font-weight: 500;
}

.ct-icon-download {
  height: 2.5rem;
  width: 2.5rem;
}

.ct-icon-download-bright {
  height: 2.5rem;
  width: 2.5rem;
}

.about-container {
   margin-bottom: 2rem !important;
}


.ct-container {
  position: relative;
}

.ct-avatar {
  position: absolute;
  transform: translateX(-2rem) translateY(-2rem);
}

.ct-avatar-small {
  position: absolute;
  transform: translateX(-0.8rem) translateY(-0.8rem);
  z-index: 10;
}

.ct-b-small-box {
  border-radius: 1.4rem !important;
}

.ct-b-small-box-22 {
  border-radius: 1.4rem !important;
  max-width: 30rem;
  margin: 0 auto;
}

.inner_container {
  width: 30%;
  padding: 0 2rem;
  margin-right: 6rem;
}

.inner_container-right {
  width: 30%;
  padding: 0 2rem;
}

.inner_container-4 {
  width: 40%;
  padding: 0 2rem;
  transform: translateX(3rem);
}

.header-part {
  height: 10rem;
}

.divide-line {
  width: 1px;
  height: 60%;
  background-color: rgb(207, 207, 207);
}

.ct-small-text {
  font-size: 0.75rem;
}

/* Global style end */

/* small screen icons slider */

.ct-icon-img {
  height: 1.2rem;
  width: auto;
}

.ct-icon-img-22 {
  height: 1.4rem;
  width: auto;
}

.sm-icon-container {
  height: 2.5rem;
  width: 2.5rem;
  border-radius: 2rem;
  background-color: white;
}

.sm-icon-container-22 {
  height: 3rem;
  width: 3rem;
  border-radius: 2rem;
  background-color: white;
}

/* Tab style start */
.nav-tab {
  border-radius: 2rem;
}

.ct-active {
  background-color: #956BE3;
  color: white !important;
  opacity: 1 !important;
 
}

.nav-tab {
  font-style: normal;
  font-size: 1.3rem;
  line-height: 1.8;
  text-transform: capitalize;
  opacity: 0.8;
  transition: 0.2s;
}



.ct-transform {
  transform: translateX(20px)
}

@media only screen and (max-width: 480px) {
  .ct-transform {
  transform: translateX(-20px)
}
}

/* Tab style end */

/* About Component start */
.ct-heading {
      font-size: 1.8rem;
  }

  .ct-card {
    border-radius: 2rem !important;
  }

  .ct-card-body {
      color: rgb(148, 147, 147);
      font-size: 1.5rem;
      line-height: 2rem;
  }

  .ct-mobile-body {
    color: rgb(73, 73, 73);
    line-height: 1.5rem;
    font-size: 0.9rem;
  }

  /* Portfolio */
  .ct-image {
    box-shadow: 0 .5rem 1rem #47559d42 !important;
    height: 20rem;
    width: 22rem;
    border-radius: 1.4rem;
  }

  /* Work */
  .ct-body-text {
      font-size: 0.9rem;
  }

  .ct-card {
      min-width: 22rem;
  }

  .rounde_me {
      border-radius: 1rem !important;
  }

  .text-content {
      font-size: 0.8rem;
      color: '#D9D8D8';
      font-weight: 300 !important;
      transform: translateY(0.5rem)
  }

  .work-tile {
      max-width: 36.4rem !important;
  }

@media only screen and (min-width: 600px) and (max-width: 960px) {
  .work-tile {
    max-width: 60rem !important;
  }
}

/* skills style */
.ct-width {
      min-width: 5.5rem;
  }

  .ct-box {
      border-radius: 0.4rem !important;
      background-color: white !important;
  }

  @media only screen and (max-width: 500px) {
    .ct-width {
      min-width: 5rem;
  }
}
</style>
