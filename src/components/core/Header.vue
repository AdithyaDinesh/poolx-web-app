<template>
  <div>
    <v-app-bar class="cover" elevate-on-scroll app>
      <v-row>
        <v-col class="ms-10" cols="1">
          <v-img
            :src="require('../../assets/logo-poolx.png')"
            contain
            height="60"
            position="left"
          />
        </v-col>
        <v-col cols="2" class="ms-n16">
          <h1 class="text-start mt-1 logo">
            Pool<span class="primary--text">X</span>
          </h1>
        </v-col>
        <v-spacer></v-spacer>
        <SignIn />
      </v-row>
    </v-app-bar>
  </div>
</template>
<style>
@import url("https://fonts.googleapis.com/css2?family=Michroma&display=swap");
.logo {
  font-family: Michroma;
}
</style>
<script>
import SignIn from "./SignIn.vue";
export default {
  components: {
    SignIn,
  },
};
</script>
