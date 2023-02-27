<template>
  <HeaderComponent title="Nation"/>
<router-view></router-view>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
export default {
  name: 'App',
  components: {
    HeaderComponent
  }
}
</script>
