<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Shop/>
    <AllItem/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import AllItem from '@/components/AllItem.vue'
import Shop from '@/components/Shop.vue'
export default {
  name: 'Home',
  components: {
    AllItem,
    Shop
  }
}
</script>
