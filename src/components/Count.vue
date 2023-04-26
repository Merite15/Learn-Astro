<template>
    <div>
        {{ count }}
        <button @click="count++"> Increment</button>
    </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const count = ref<number>(0)

</script>