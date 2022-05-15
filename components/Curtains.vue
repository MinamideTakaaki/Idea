<template>
	<div class="curtain">
		<div class="invert">
			<h2>甲陽学院高等学校</h2>
		</div>
	</div>
</template>

<style scoped>
  .curtain {
  	background-image: linear-gradient(to bottom, var(--color2) 50%, var(--color1) 50%);
  }
  .curtain::after {
  	content: "";
  	display: block;
  	min-height: var(--minh);
  }

  .invert {
  	position: sticky;
  	top: 20px;
  	mix-blend-mode: difference;
  	display: flex;
  	align-items: center;
  	justify-content: center;
  	min-height: var(--minh);
  }

  h2 {
  	font-size: 60px;
  	color: var(--color1);
  }
</style>