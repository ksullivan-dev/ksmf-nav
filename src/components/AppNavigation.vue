<template>
  <ul>
    <li>
      <router-link to="/">Home</router-link>
    </li>
    <li>
      <router-link to="/orders">Orders</router-link>
    </li>
    <li>
      <router-link to="/orders/sub">Orders > Sub</router-link>
    </li>
    <li>
      <router-link to="/orders/nope">Orders > Nope</router-link>
    </li>
  </ul>
</template>

<script>
  export default {
    name: "AppNavigation",
  };
</script>
