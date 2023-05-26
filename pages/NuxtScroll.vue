<script>
export default {
  setup() {

		useHead({
		  title: 'title',
		  meta: [
		    { name: 'description', content: 'title' }
		  ],
		})
    return {

    }
  }
}
</script>
<template>
	<div class="w-full h-screen bg-gray-900 flex justify-center items-center">
		<div class="flex flex-row space-x-1 w-full h-80 px-20">
			<div 
			v-for="i in 4"
			class="bg-white rounded-[12px] shadow-xl bg-center bg-cover h-full flex flex-1 hover:flex-[70%] duration-300 ease-linear" 
			style="background-image: url(https://img.freepik.com/free-photo/full-shot-travel-concept-with-landmarks_23-2149153258.jpg?3&w=2000&t=st=1685018890~exp=1685019490~hmac=7a28edcc1558a8074b7a56cef554b594599b6912486df0294275a964c78b595c);">

			</div>
		</div>
	</div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Anton&display=swap');
  @import "https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css";
  
  body,html {
  	font-family: 'Anton', sans-serif;
  };


.my-name:hover {
 cursor:url(http://www.picgifs.com/smileys/smileys-and-emoticons/money/smileys-money-671353.gif), auto;
}



.dev:hover {
 cursor:url(http://www.picgifs.com/smileys/smileys-and-emoticons/money/smileys-money-671353.gif), auto;
}


</style>