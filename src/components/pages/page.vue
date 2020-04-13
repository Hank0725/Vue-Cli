<template>
  <div class="hello">
    <router-link to="/page/child">卡片1</router-link>
      <router-link to="/page/child2">卡片2</router-link>
        <router-link to="/page/child3">卡片3</router-link>
   <div class="card" style="width: 18rem;">
  <div class="card-body">
    <router-view></router-view>
  </div>
  </div>
   </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

