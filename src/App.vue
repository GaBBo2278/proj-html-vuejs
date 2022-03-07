<template>
  <div id="app">
    <MyHeader :listHeader="this.headerList" :listHeaderRight="this.headerRight"/>
    <JumbotronSection/>
    <TogetherSection/>
    <ExploreSection/>
    <VideoSection/>
    <UpcomingSection/>
    <ReviewsSection/>
    <SubscribeSection/>
    <MyFooter/>

  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'
import JumbotronSection from './components/JumbotronSection.vue'
import TogetherSection from './components/TogetherSection.vue'
import ExploreSection from './components/ExploreSection.vue'
import VideoSection from './components/VideoSection.vue'
import UpcomingSection from './components/UpcomingSection.vue'
import ReviewsSection from './components/ReviewsSection.vue'
import SubscribeSection from './components/SubscribeSection.vue'
export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    JumbotronSection,
    TogetherSection,
    ExploreSection,
    VideoSection,
    UpcomingSection,
    ReviewsSection,
    SubscribeSection
  },
  data: function() {
        return {
            headerList: [
              {
                item: "Home",
                active: false
              },
              {
                item: "Pages",
                active: false
              },
              {
                item: "Courses",
                active: false
              },
              {
                item: "Features",
                active: false
              },
              {
                item: "Blog",
                active: false
              },
              {
                item: "Shop",
                active: false
              }
            ],
            headerRight : [
              {
                langFlag: "en.png",
                language: "ENGLISH"
              },
              {
                langFlag: "de.png",
                language: "GERMAN"
              },
              {
                langFlag: "fr.png",
                language: "FRENCH"
              }
            ]
        }
    }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
@import './style/general.scss';
@import './style/mixins.scss';
@import '~@fortawesome/fontawesome-free/css/all.min.css';
#app {
  font-family: 'Poppins', sans-serif;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>