<template>
    <div>
        <app-header />
        <!-- <app-footer/> -->
        <div class="container">

        </div>
    </div>
</template>

<script setup>
    // import { ref } from 'vue';
    // const name = ref('Francies');
    import Cars from '@/components/Cars/index.vue'
    import CarBrands from '@/components/Cars/brands.vue'
    import { reactive, provide } from 'vue';
    
</script>

<style>
    body {
        padding: 0;
        margin: 0;
        font-family: 'Roboto', sans-serif;
    }
    .container {
        min-height: 84vh;
        box-sizing: border-box;
        padding: 20px;
    }

</style> 