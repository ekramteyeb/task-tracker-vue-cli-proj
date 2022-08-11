<template>
  <button :style="{background:color}" @click="onClick()" class="btn">
        {{text}}
  </button>
</template>

<script>
export default {
    name: 'ButtonT',
    props: {
        text: String,
        color:String
    }, 
    methods: {
        onClick() {
            console.log('am clicked')
        }
    }
}
</script>

<style scoped>
   
</style>