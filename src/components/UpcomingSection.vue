<template>
<div class="wrapper-bg">
  <section class="upcoming">
      <div class="container-60">
          <h2 class="text-center">Wanna Transform your life?</h2>
          <h1 class="text-center">Upcoming Events</h1>
          <div class="event-list">
              <div class="event">
                  <div class="info">
                      <span><i class="fas fa-map-marker-alt"></i><p>Texas, US</p></span>
                      <h3>Storytelling Workshop</h3>
                  </div>
                  <div class="tickets text-center">
                      <h1 class="smaller">22</h1>
                      <h3>NOV</h3>
                      <button class="button-full">Get ticket</button>
                  </div>
              </div>
              <div class="event">
                  <div class="info">
                      <span><i class="fas fa-map-marker-alt"></i><p>Texas, US</p></span>
                      <h3>Storytelling Workshop</h3>
                  </div>
                  <div class="tickets text-center">
                      <h1 class="smaller">22</h1>
                      <h3>NOV</h3>
                      <button class="button-full">Get ticket</button>
                  </div>
              </div>
              <div class="event">
                  <div class="info">
                      <span><i class="fas fa-map-marker-alt"></i><p>Texas, US</p></span>
                      <h3>Storytelling Workshop</h3>
                  </div>
                  <div class="tickets text-center">
                      <h1 class="smaller">22</h1>
                      <h3>NOV</h3>
                      <button class="button-full">Get ticket</button>
                  </div>
              </div>
              <div class="event">
                  <div class="info">
                      <span><i class="fas fa-map-marker-alt"></i><p>Texas, US</p></span>
                      <h3>Storytelling Workshop</h3>
                  </div>
                  <div class="tickets text-center">
                      <h1 class="smaller">22</h1>
                      <h3>NOV</h3>
                      <button class="button-full">Get ticket</button>
                  </div>
              </div>
              <div class="event">
                  <div class="info">
                      <span><i class="fas fa-map-marker-alt"></i><p>Texas, US</p></span>
                      <h3>Storytelling Workshop</h3>
                  </div>
                  <div class="tickets text-center">
                      <h1 class="smaller">22</h1>
                      <h3>NOV</h3>
                      <button class="button-full">Get ticket</button>
                  </div>
              </div>
              <div class="event">
                  <div class="info">
                      <span><i class="fas fa-map-marker-alt"></i><p>Texas, US</p></span>
                      <h3>Storytelling Workshop</h3>
                  </div>
                  <div class="tickets text-center">
                      <h1 class="smaller">22</h1>
                      <h3>NOV</h3>
                      <button class="button-full">Get ticket</button>
                  </div>
              </div>
          </div>
          <div class="view-all-events">
                <p class="text-center">Excited about our event?<span><a href="">View all events <i class="fas fa-arrow-right"></i></a></span></p>
            </div>

      </div>
  </section>
  </div>
</template>

<script>
export default {
    name: 'UpcomingSection'
}
</script>

<style scoped lang="scss">
@import '../style/general.scss';
@import '../style/mixins.scss';
h2 {
    font-size: $h2;
    color: $mountainMeadow;
}
h1 {
    font-size: $h1;
    color: $charade;
    font-weight: 600;
}
h3 {
    font-size: $h3;
    color: $charade;
}
.wrapper-bg {
    background-color: $linkWater;
}
.upcoming {
    background-color: $white;
    padding: 80px 0;
    border-bottom-right-radius: 300px;
}
.event-list {
    @include flex;
    flex-wrap: wrap;
    .event {
        width: calc(50% - 10px);
        margin: 5px;
        background-color: $linkWater;
        @include flex;
        padding: 16px;
        border-radius: 6px;
        .smaller {
                color: $mountainMeadow;
                font-weight: normal;
                margin: 0;
            }
        .info {
            h3 {
                margin-top: 8px;
            }
            span {
                font-size: $smallText;
                color: $boulder;
                & p {
                    margin-left: 6px;
                    display: inline;
                }
            }
        }
    }
}
.view-all-events {
    width: 35%;
    margin: auto;
    padding-top: 30px;
    p {
        font-size: $mediumSmallText;
        font-weight: 600;
        color: $boulder;
        line-height: 24px;
        a {
            padding-left: 6px;
           color: $mountainMeadow;
           font-weight: 700;
           text-underline-offset: 4px;
           text-decoration-color: $silver;
        }
    }
}
</style>