<template>
  <div class="home">
    <div class="wrapper">
      <div class="main">
        <blog-list></blog-list>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import BlogList from '@/components/BlogList'
export default {
  name: "Home",
  components:{
    BlogList
  }
};
</script>
