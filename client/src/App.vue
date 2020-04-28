<template>
  <div id="app">
    <Header />
    <VideoPlayer channelId="xqcow" />
    <VideoPlayer channelId="sonysandiegostudio" />
    <VideoPlayer channelId="scoped" />
    <VideoPlayer channelId="fextralife" />
  </div>
</template>

<script>
import Header from './components/Header'
import VideoPlayer from './components/VideoPlayer'

export default {
  name: 'App',
  components: {
    Header,
    VideoPlayer
  }
}
</script>

<style>
* {
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
