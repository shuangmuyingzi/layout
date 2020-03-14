<template>
    <div class="page-container">
				<div class="content-container">
					<div class="content">
            DHDD
		      </div>
		    </div>
		</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .content-container {
			position: absolute;
			top: 0;
			left: 0;
			right: 0;
			bottom: 0;
			overflow: scroll;
		}

		.content{
			width: 90%;
			height: 80%;
			background: #333;
			position: absolute;
			border-radius: 20px;
			left: 50%;
			top: 50%;
			transform: translate(-50%, -50%);
		}
</style>
