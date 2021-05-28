<template>
  <div class="container" style="text-align: center">
    <h1>Portfolio</h1>
    <p>---------------------------------------</p>
    <div>
      <router-link :to="{ name: 'profile' }">
        <img src="@/assets/b1.png" />
      </router-link>
    </div>
    <div>
      <router-link :to="{ name: 'contact' }">
        <img src="@/assets/b2.png" />
      </router-link>
    </div>
    <p>---------------------------------------</p>
  </div>
</template>