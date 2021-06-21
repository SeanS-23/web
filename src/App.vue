<template>
  <v-app>
    <v-app-bar app dark hide-on-scroll elevation="0" color="#0A182F">
      <v-icon size="32"> mdi-boxing-glove </v-icon>
      <v-spacer />
      <v-btn href="#about" text class="pl-3 pr-3 text-none">
        <v-text class="text-none teal--text text--accent-1 pr-1"> 01. </v-text>
        About
      </v-btn>
      <v-btn href="#experience" text class="pl-3 pr-3 text-none">
        <v-text class="text-none teal--text text--accent-1 pr-1"> 02. </v-text>
        Experience
      </v-btn>
      <v-btn href="#projects" text class="pl-3 pr-3 text-none">
        <v-text class="text-none teal--text text--accent-1 pr-1"> 03. </v-text>
        Projects
      </v-btn>
      <v-btn href="#contact" text class="pl-3 pr-3 text-none">
        <v-text class="text-none teal--text text--accent-1 pr-1"> 04. </v-text>
        Contact
      </v-btn>
      <v-btn color="teal accent-1" outlined class="pl-3 pr-3 text-none">
        Resume
      </v-btn>
    </v-app-bar>

    <login />
  </v-app>
</template>

<script>
import Login from '@/components/Login.vue'

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style>

.login-time {
  color: black !important;
  background: black;
  background-color: black !important;
  height: 200px;
  width: 400px;
  position: relative;
}

</style>
