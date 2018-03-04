<template>
	<img :src="url" :alt="titulo" class="imagem-responsiva">
</template>

<script>
	export default {
		props: ['url', 'titulo']
	}
</script>

<style scoped>

	.imagem-responsiva {
		display: block;
	    max-width: 100%;
	    height: auto;
	}

</style>