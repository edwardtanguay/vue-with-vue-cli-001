<template>
  <div class="hello">
    <p>
      This is a new component with the message "{{message}}".
    </p>
  </div>
</template>

<script>
export default {
  name: 'InfoSpace',
  props: {
    message: String
  }
}
</script>

<style scoped>
	p {
		color: black;
		text-shadow: .1rem .1rem .3rem orange;
		font-size: 2rem;
	}
</style>
