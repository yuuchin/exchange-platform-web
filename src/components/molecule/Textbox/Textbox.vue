<template>
  <div class="flex flex-col">
    <label for="name" class="text-gray-600 mt-3 h-auto w-52 text-left p-2">{{ text }}</label>
    <input class="border-4 border-gray-400 rounded-lg p-1.5" type="text" :placeholder="name" id="name">
  </div>

</template>

<script>
export default {
  name: "Textbox",

  props: {
    text: {
      type: String,
      required: true,
    },
    name: {
      type: String,
      required: false
    }
  }
}

</script>

<style scoped>

</style>
