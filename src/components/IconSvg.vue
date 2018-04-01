<template>
  <svg class="svg-icon" aria-hidden="true">
    <use :xlink:href="iconName"></use>
  </svg>
</template>

<script>
export default {
  name: 'icon-svg',
  props: {
    iconClass: {
      type: String,
      required: true
    }
  },
  computed: {
    iconName() {
      return `#icon-${this.iconClass}`
    }
  }
}
</script>

<style lang="less">
	.svg-icon {
	  width:100%;
	  height:100%;
    vertical-align:0;
    fill: currentColor;
	  overflow: hidden;  
	}	
</style>