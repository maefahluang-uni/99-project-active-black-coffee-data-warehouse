<template>
  <div>
    <v-row class="ma-0" >
      <v-img src="/mfu_bg.png" cover max-height="30rem">
        <v-row no-gutters align="center" justify="center" class="fill-height">
          <v-col cols="8" md="6">
            <v-row>
              <v-text-field
                rounded="lg"
                bg-color="white"
                label="Search Datasets"
                variant="solo"
              ></v-text-field>
            </v-row>

            <v-row justify="center">
              <v-card
                v-ripple
                rounded="lg"
                color="primary"
                class="cursor-pointer pa-3"
              >
                <v-icon> mdi-magnify </v-icon>
                Search
              </v-card>
            </v-row>

            <v-row justify="center" class="mt-7">
              <v-card
                v-ripple
                rounded="lg"
                color="primary"
                class="cursor-pointer pa-3"
              >
                <v-icon> mdi-chart-line </v-icon>
                420
              </v-card>
            </v-row>
          </v-col>
        </v-row>
      </v-img>
    </v-row>

    <v-row class="fill-height mt-2" no-gutters align="center">
      <v-row align="center">
        <v-col>
          <v-divider style="opacity: 1" color="secondary " thickness="4" />
        </v-col>

        <v-col cols="2" md="1">
          <div class="text-center text-h5 font-weight-bold">Group</div>
        </v-col>

        <v-col>
          <v-divider style="opacity: 1" color="secondary " thickness="4" />
        </v-col>
      </v-row>
    </v-row>

    <v-row>
      <v-col cols="1" md="2" lg="3"> </v-col>

      <v-col>
        <v-row>
          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >School</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >Centre</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >Institution</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >Academic Office</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-white text-center fill-height d-flex align-center justify-center"
                >Central Administrative Office</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >University Council Office</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >Internal Audit
              </span>
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-white text-center fill-height d-flex align-center justify-center"
                >Property and Asset Management Office</span
              >
            </v-card>
          </v-col>

          <v-col cols="6" md="4" class="d-flex justify-center">
            <v-card
              v-ripple
              class="cursor-pointer custom-card"
              width="180px"
              height="80px"
            >
              <span
                class="text-h6 text-white text-center fill-height d-flex align-center justify-center"
                >Special Unit</span
              >
            </v-card>
          </v-col>
        </v-row>
      </v-col>

      <v-col cols="1" md="2" lg="3"> </v-col>

      <v-divider
        class="mt-10"
        style="opacity: 1"
        color="secondary "
        thickness="4"
      />
    </v-row>

 
  </div>
</template>

<script setup>
import { ref } from "vue";

const value = ref(new Date());
</script>

<style scoped>
.custom-card {
  background: linear-gradient(
    to bottom,
    rgb(var(--v-theme-primary)) 80%,
    rgb(var(--v-theme-secondary)) 100%
  );
}

.sometest{
  color: red;
}
</style>
