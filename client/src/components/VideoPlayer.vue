<template>
  <div id='video-player'>
    <iframe :src="'https://player.twitch.tv/?channel=' + channelId" frameborder="0" allowfullscreen="false" scrolling="no" height="100%" width="100%" />
  </div>
</template>

<script>
export default {
  name: 'VideoPlayer',
  props: {
    channelId: String
  }
}
</script>

<style scoped>
#video-player {
  width: 25%;
  height: 25%;
  background-color: grey;
}
</style>