<template>
  <div class="app-container" id="app">
    <div class="bg"></div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
    @import '../static/css/reset.css';
    html{
      height: 100%;
    }
    body,
		.index-container,
		.app-container,
		.page-container {
			width: 100%;
			height: 100%;
			overflow: hidden;
		}
		.app-container {
			position: relative;
		}
		.page-container {
			position: absolute;
			top: 0;
			left: 0;
			right: 0;
			bottom: 0;
			overflow: hidden;
    }
    .bg{
			position: absolute;
			top: 0;
			left: 0;
			right: 0;
			bottom: 0;
			background: url('../static/img/bg.jpeg') no-repeat;
			background-size: 100% 100%;
		}
</style>
