<!--
 * @Author: matu-lgs 442285570@qq.com
 * @Date: 2024-07-14 09:15:36
 * @LastEditors: matu-lgs 442285570@qq.com
 * @LastEditTime: 2024-07-14 10:05:25
 * @FilePath: /bilibilbi/pages/index/index.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>{{ res }}</template>
<script setup lang="ts">
const { data: res } = await useFetch("/api/hello");
</script>
