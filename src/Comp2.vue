<script setup>
defineProps({
	disabled: {
		type: Boolean,
		default: false
	},
	count: {
		type: Number,
		default: 0
	}
})
</script>

<template>
	<div>disabled = {{ disabled }}</div>
	<p><button :disabled="disabled">Кнопка {{ count }}</button></p>
</template>
