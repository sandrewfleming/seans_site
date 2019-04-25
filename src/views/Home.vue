<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/headshot.jpg" id="img" />
    <HelloWorld msg="Sean Fleming" />
  </div>
</template>
<style>
 #img{
height:25%;
width:25%;
float:left;
padding-top:35px;
}
  
</style>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
