<script setup lang="ts">
  import '~/assets/css/app.css'
</script>

<template>
  <main>
    <div class="menu">
      <ul>
        <li>
          <NuxtLink to="/">/</NuxtLink>
          <NuxtLink to="/about">/about</NuxtLink>
          <NuxtLink to="/users/samit?type=admin&page=1">/users/samit?type=admin&page=1</NuxtLink>
          <NuxtLink to="/category/cloth">category/cloth</NuxtLink>
          <NuxtLink to="/backend/dashboard/recent/2024/04/17">/backend/dashboard/recent/2024/04/17</NuxtLink>
          <NuxtLink to="/parent/child">/parent/child</NuxtLink>
          <NuxtLink to="/parent/sister">/parent/sister</NuxtLink>
        </li>
      </ul>
    </div>
    <div class="content">
      <NuxtPage />
    </div>
  </main>
</template>

<style scoped>
  /* @import url('~/assets/css/app.css') */

  /* main {
    display: flex;
  }
  .menu {
    width: 400px;
    padding: 20px;
  }
  ul li {
    list-style-type: none;
    padding: 0;
    margin: 0;
  }
  .content {
    flex: 1;
    padding: 20px;
    border: 1px solid #333;
    margin-top: 36px;
    border-radius: 5px;
    margin-right: 50px;
  }

  ul li a {
    color: #333;
    text-decoration: none;
    display: block;
    border: 1px solid #333;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
    word-wrap: break-word;
  }

  ul li a:hover {
    background-color: #333;
    color: #fff;
  }

  .router-link-active {
    background-color: #333;
    color: #fff;
  } */
</style>
