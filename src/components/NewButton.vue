<template>
    <h1>Count: {{count}}</h1>
    <button type="buttton" @click="clickOnMe">Click on me</button>
</template>

<script>
export default{
  data() {
    return {
      count: 0
    }
  },
  methods: {
    clickOnMe() {
      this.count += 1
    }
  }
}
</script>
