<template>
    <p>{{ greeting }} World!</p>
</template>

<script>
module.exports = {
	data: function() {
		return {
			greeting: 'Hello'
		};
	}
};
</script>

<style scoped>
p {
	font-size: 16pt;
	text-align: center;
}
</style>
