<script setup>
import ScrollyVideo from 'scrolly-video/dist/ScrollyVideo.vue'

</script>
<template>
	<div class="relative w-full h-full">
		<div class="h-[300px] flex justify-center items-center">
			<h1 class="text-[42px]">Hello</h1>
		</div>
		<ScrollyVideo src="https://scrollyvideo.js.org/goldengate.mp4" class="h-[1200px]"/>
		<div class="h-[5300px] flex justify-center items-center">
			<h1 class="text-[42px]">Hello</h1>
		</div>
	</div>
	<div class="h-[300px] flex justify-center items-center">
			<h1 class="text-[42px]">Footer</h1>
		</div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Anton&display=swap');
  @import "https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css";
  
  body,html {
  	font-family: 'Anton', sans-serif
  }



</style>