<script>
export default {
  props: {
    color: {
      type: String,
      default: "#323232"
    }
  }
}
</script>

<template>
<svg width="24px" height="24px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M9 12H15" :stroke="color" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M12 9L12 15" :stroke="color" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12Z" :stroke="color" stroke-width="2"/>
</svg>
</template>