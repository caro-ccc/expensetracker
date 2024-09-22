<template>
    <div>
    <h3>HISTORIAL</h3>
    <ul id="list" class="list">
        <li v-for="transaction in transactions" 
        v-bind:key="transaction.id">
        {{ transaction.text }}
        <span>-${{ transaction.amount }}</span>
        <button class="delete-btn">X</button>
    </li>
    <button class="delete-btn"></button>
        
        
    </ul>
</div>
</template>
<script setup>
import {defineProps} from 'vue';
const props = defineProps({
    trasicationes: {
        type: Array,
        required: true,
    }
})
</script>




