<template>
	<div class="hello">
		<div class="header">{{ msg }}</div>

		<div class="card">
			<div class="title border-bottom">这里其实什么都没有</div>
			<div class="title border-bottom">直接开始开发吧</div>
		</div>
		
	</div>
</template>

<script>
export default {
	name: "HelloWorld",
	data() {
		return {
		msg: "基础开发环境"
		};
	}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
</style>
