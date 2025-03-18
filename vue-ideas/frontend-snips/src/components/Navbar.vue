<script setup>
import { ref } from "vue"

// here we'll put the most common routes that could be used to check out weird app ideas.

const navList = ["Slider 1", "Confetti Spray"]

</script>

<template>
<ul>
    <li v-for="navItem in navList">
        {{navItem}}
    </li>
</ul>


</template>

<style>

</style>