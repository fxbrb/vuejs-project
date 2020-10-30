<template>
  <div class="bg-blue-300 p-2">
    <a href="#" @click="changeComponent('cours-view')">Tous mes cours</a> | 
    <a href="#" @click="changeComponent('selection-list')">Mes cours préférés</a>
  </div>
</template>

<script>
export default {
  name: "nav-bar",
  methods: {
    changeComponent(value) {
      this.$emit('change-component', value)
    }
  }
}
</script>

<style>

</style>