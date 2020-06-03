<template>
  <div class="wrap">
    <content-loader
		:height="475"
		:width="500"
		:speed="10"
		primaryColor="#f3f3f3"
		secondaryColor="#ecebeb"
	>
		<circle cx="30" cy="30" r="30" /> 
		<rect x="75" y="13" rx="4" ry="4" width="100" height="13" /> 
		<rect x="75" y="37" rx="4" ry="4" width="50" height="8" /> 
		<rect x="0" y="70" rx="5" ry="5" width="400" height="400" />
	</content-loader>
  </div>
  
</template>

<script>
import { ContentLoader } from 'vue-content-loader'

export default {
  components: {
    ContentLoader 
  }
}
</script>

<style scoped>
.wrap {
  height: 700px;
  width: 600px;
  margin: 30px auto;
}
</style>