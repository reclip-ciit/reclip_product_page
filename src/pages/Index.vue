<template>
  <q-page>
    <q-dialog v-model="alert">
      <q-card>
        <q-card-section>
          <div class="text-h6">Coming Soon!</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
          Awwww 🙁, don't worry! Reclip is coming soon on Google Play Store!
          Always check the website for further updates!
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!-- Start of Landing Page *-->
    <!-- Mobile -->
    <div class="flex flex-center fit lt-sm ">
      <div class="row justify-center items-center q-mt-xl q-mt-md-none">
        <div class="col-12 col-md">
          <div class="flex flex-center full-width">
            <div class="holder">
              <img src="../assets/android_phone_frame.png" alt="" />
              <div class="carousel-wrapper">
                <q-carousel
                  v-model="slide"
                  transition-prev="slide-right"
                  transition-next="slide-left"
                  animated
                  autoplay
                >
                  <q-carousel-slide class="q-pa-none" name="1">
                    <img
                      src="../assets/app_screenshots/sc_1.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="2">
                    <img
                      src="../assets/app_screenshots/sc_2.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="3">
                    <img
                      src="../assets/app_screenshots/sc_3.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="4">
                    <img
                      src="../assets/app_screenshots/sc_4.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="5">
                    <img
                      src="../assets/app_screenshots/sc_5.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="6">
                    <img
                      src="../assets/app_screenshots/sc_6.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="7">
                    <img
                      src="../assets/app_screenshots/sc_7.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="1">
                    <img
                      src="../assets/app_screenshots/sc_1.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                </q-carousel>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md justify-center q-pa-lg">
          <p
            class="text-white text-h5 text-center "
            style="margin-left:auto; margin-right:auto; display:block"
          >
            Reclip a multimedia marketing platform, by CIIT Senior Highschool
            Students.
          </p>
          <img
            @click="alert = true"
            src="../assets/google-play-badge.png"
            alt="download now"
            style="margin-left:auto; margin-right:auto; display:block; max-height:100px;"
          />
        </div>
      </div>
    </div>

    <!-- Desktop -->
    <div class="flex flex-center window-height gt-xs ">
      <div class="row justify-center items-center q-mt-xl q-mt-md-none">
        <div class="col-12 col-md">
          <div class="flex flex-center full-width">
            <div class="holder">
              <img src="../assets/android_phone_frame.png" alt="" />
              <div class="carousel-wrapper">
                <q-carousel
                  v-model="slide"
                  transition-prev="slide-right"
                  transition-next="slide-left"
                  animated
                  autoplay
                >
                  <q-carousel-slide class="q-pa-none" name="1">
                    <img
                      src="../assets/app_screenshots/sc_1.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="2">
                    <img
                      src="../assets/app_screenshots/sc_2.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="3">
                    <img
                      src="../assets/app_screenshots/sc_3.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="4">
                    <img
                      src="../assets/app_screenshots/sc_4.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="5">
                    <img
                      src="../assets/app_screenshots/sc_5.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="6">
                    <img
                      src="../assets/app_screenshots/sc_6.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="7">
                    <img
                      src="../assets/app_screenshots/sc_7.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                  <q-carousel-slide class="q-pa-none" name="1">
                    <img
                      src="../assets/app_screenshots/sc_1.png"
                      class="full-height full-width q-pt-none fit"
                      alt=""
                    />
                  </q-carousel-slide>
                </q-carousel>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md justify-center q-pa-lg">
          <p
            class="text-white text-h5 text-center "
            style="margin-left:auto; margin-right:auto; display:block"
          >
            Reclip a multimedia marketing platform, by CIIT Senior Highschool
            Students.
          </p>
          <img
            @click="alert = true"
            src="../assets/google-play-badge.png"
            alt="download now"
            style="margin-left:auto; margin-right:auto; display:block; max-height:100px;"
          />
        </div>
      </div>
    </div>
    <!--  End of Landing Page  -->

    <!--  Start of Team Page  -->
    <!-- Mobile -->
    <div class="flex developers lt-md">
      <div class="fit text-center">
        <div class="text-h4 text-white text-bold q-pt-xl">The Reclip Team</div>

        <div class="q-my-lg">
          <q-avatar size="200px">
            <img class="shadow-2" src="../assets/paolo_profile.jpg" alt="" />
          </q-avatar>
          <div class="text-h4 text-bold q-pt-md">Paolo Tolentino</div>
        </div>
        <div class="q-my-lg">
          <q-avatar size="200px">
            <img class="shadow-2" src="../assets/vincent_profile.png" alt="" />
          </q-avatar>
          <div class="text-h4 text-bold q-pt-md">Vincent Alfaro</div>
        </div>
        <div class="q-my-lg">
          <q-avatar size="200px">
            <img class="shadow-2" src="../assets/gervacio_profile.png" alt="" />
          </q-avatar>
          <div class="text-h4 text-bold q-pt-md">Ryan Gervacio</div>
        </div>
      </div>
    </div>

    <!-- Desktop -->
    <div class="flex flex-center developers window-height gt-sm">
      <div class="full-width text-center">
        <div class="headline text-h2 text-white text-bold">The Reclip Team</div>
        <div class="row justify-center items-start fit">
          <div class="col-12 col-md-2 q-px-lg">
            <q-avatar class="fit shadow-2">
              <img src="../assets/paolo_profile.jpg" alt="" />
            </q-avatar>
            <div class="text-h5 q-pt-md">Paolo Tolentino</div>
          </div>
          <div class="col-12 col-md-2 q-px-lg">
            <q-avatar class="fit shadow-2">
              <img src="../assets/vincent_profile.png" alt="" />
            </q-avatar>
            <div class="text-h5 q-pt-md">Vincent Alfaro</div>
          </div>
          <div class="col-12 col-md-2 q-px-lg">
            <q-avatar class="fit shadow-2">
              <img src="../assets/gervacio_profile.png" alt="" />
            </q-avatar>
            <div class="text-h5 q-pt-md">Ryan Gervacio</div>
          </div>
        </div>
      </div>
    </div>
    <!--  End of Team Page  -->
  </q-page>
</template>

<script>
export default {
  name: "IndexPage",

  data() {
    return { alert: false, slide: 1 };
  }
};
</script>

<style scoped>
.holder {
  position: relative;
  /* left: 13%; */
  display: inline-block;
}
.developers {
  background: #6f79a8;
}
.headline {
  padding-bottom: 150px;
}

.carousel-wrapper {
  position: absolute;
  top: 49px;
  bottom: 10px;
  left: 10px;
  right: 10px;
  z-index: -1;
}
</style>
