<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <v-spacer/>

      <div class="d-flex align-center">
        <h2>William Skaggs</h2>
      </div>

      <v-spacer/>
      <v-spacer/>
      <v-spacer/>
      <v-spacer/>
      <v-spacer/>

      <v-btn
          href="https://github.com/iamwood"
          target="_blank"
          fab
          small
          color="secondary"
      >
        <v-icon dark>
          mdi-file
        </v-icon>
      </v-btn>

      <v-btn
        href="https://github.com/iamwood"
        target="_blank"
        fab
        small
        color="secondary"
      >
        <v-icon dark>
          mdi-github
        </v-icon>
      </v-btn>

      <v-spacer/>

    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import { mdiGithub } from '@mdi/js'
import { mdiFile } from '@mdi/js'

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    icons: {
      mdiGithub,
      mdiFile
    }
  }),
};
</script>
<style>

@import url('https://fonts.googleapis.com/css2?family=Inconsolata&display=swap');

h2 {
  font-family: 'Inconsolata', monospace;
}

</style>