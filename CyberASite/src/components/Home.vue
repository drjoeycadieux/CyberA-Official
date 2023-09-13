<script setup>
import Header from './Header.vue'
import Alerts from './Alerts.vue'
</script>


<template>
    <div>
        <Alerts />
        <Header />
    </div>
    <div class="home">
        <p>
            Home Page
        </p>
    </div>
</template>


<style scoped>
.home {
    padding: 15px;
    box-sizing: border-box;
}

.home p {
    text-align: center;
    font-family: sans-serif;
    font-size: 35px;
    font-weight: bold;
}
</style>