<!--
 * @Author: matu-lgs 442285570@qq.com
 * @Date: 2024-07-14 09:15:42
 * @LastEditors: matu-lgs 442285570@qq.com
 * @LastEditTime: 2024-07-14 10:18:45
 * @FilePath: /bilibilbi/pages/video/index.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>{{ post }}</template>
<script setup lang="ts">
const { data: post } = await useFetch("/api/video/b");
</script>
