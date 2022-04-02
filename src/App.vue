<template>
  <v-app>
    <v-container>
      <v-row justify="center">
        <v-col md="6">
          <video-player />
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import VideoPlayer from './components/VideoPlayer'

export default {
  name: 'App',
  components: {
    VideoPlayer
  }
}

</script>