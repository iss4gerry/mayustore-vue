<script setup lang="ts">
    
</script>

<template>
    <div id="nav-bar">
        <router-link :to="{ name: 'product' }" id="products-link">Product</router-link>
        <router-link :to="{ name: 'cart' }" id="cart-link">
            <button>Cart</button>
        </router-link>
    </div>
</template>

<style scoped>
#nav-bar {
    border-bottom: 1px solid #ddd;
    height: 75px;
    width: 100%;
  }
  #products-link {
    text-align: center;
    display: block;
    color: #41B883;
    font-size: 42px;
    font-weight: bold;
    left: 32px;
    position: absolute;
    top: 16px;
    text-decoration: none;
  }
  #products-link h1 {
      margin: 0;
  }
  #cart-link {
    position: absolute;
    right: 16px;
    top: 16px;
  }
</style>