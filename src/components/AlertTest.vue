<template>
  <div>
    <label for="text">Text: </label>
    <input id="text" type="text" v-model="text" placeholder="input text..." />
    <button @click="alertText">Submit</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: ""
    }
  },
  methods: {
    alertText() {
      alert(this.text)
    }
  }
}
</script>

<style scoped></style>
