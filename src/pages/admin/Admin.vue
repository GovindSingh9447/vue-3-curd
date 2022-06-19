<template>

  <Nav/>
  <SiderBar/>
  <router-view/>
</template>

<script>
import Nav from '@/components/Nav.vue'
import SideBar from '@/components/SideBar.vue'
export default {

    name:"Admin",
    components:{Nav,SideBar}

}
</script>

<style>

</style>