<template>
	<div class="jumbo">
		<span>Hero</span>
	</div>
</template>

<script>
export default {
	name: "Hero",
	props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.jumbo {
	margin-top: 20px;
	height: 300px;
	width: 100%;
	border: 1px solid black;
	display: flex;
	justify-content: center;
	align-items: center;
	background-color: #abed;
}
.jumbo span {
	color: pink;
	font-size: 40px;
}
</style>
