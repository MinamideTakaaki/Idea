<template>
	<nav>
		<div>あああ</div>
		<div>いいい</div>
		<div>ううう</div>
		<div>えええ</div>
		<div>おおお</div>
		<div>かかか</div>
	</nav>
</template>

<style>
	nav {
		width: 80vw;
		height: 8vh;
		background-color: rgba(10, 128, 171, .9);
		position: fixed;
		inset: 0;
		margin: auto auto 8vh;
		border-radius: 4vh;
		display: flex;
		justify-content: center;
	}

	nav > div {
		width: 15vh;
		height: 5vh;
		margin: 1.5vh 0;
		border-right: 3px solid white;
		color: white;
		text-align: center;
		line-height: 5vh;
	}
	nav > div:last-child {
		border: none;
	}
</style>