<!--
 * @Author: matu-lgs 442285570@qq.com
 * @Date: 2024-07-05 18:23:33
 * @LastEditors: matu-lgs 442285570@qq.com
 * @LastEditTime: 2024-07-14 11:41:19
 * @FilePath: /bilibilbi/app.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtPage :keepalive="{ max: 10 }" />
    <ul>
      <li>
        <NuxtLink to="/"><van-button type="primary">home</van-button></NuxtLink>
      </li>
      <li>
        <NuxtLink to="/video"
          ><van-button type="success">video</van-button></NuxtLink
        >
      </li>
    </ul>

    <ul>
      <li v-for="item in [1, 2, 3]">{{ item }}</li>
    </ul>
    hellowo
  </div>
</template>
<script setup lang="ts">
useSeoMeta({
  title: "bilibili",
  description: "my bilibili",
  keywords: "bib",
});
</script>
<style>
/* @import "./assets/styles/main.sass"; */
:root {
  --van-primary-color: #fb7299;
}
</style>
