<script setup lang="ts">

    // import { MyButton } from 'my-component-lib';
    // import '/node_modules/my-component-lib/dist/style.css';

    //import MyButton from '@/components/MyButton.vue'
    //import { MyButton } from 'my-component-lib'
    // import 'my-component-lib/style.css'

</script>


<template>
    <div>
        <div style="padding-bottom:20px; text-align:center;">BUTTON TEST</div>
        <!--MyButton>Testing</MyButton-->
    </div>
</template>


<style>

    @import './assets/base.css';

    #app {
        max-width: 1280px;
        margin: 0 auto;
        padding: 2rem;
        font-weight: normal;
    }

    .btn {
        padding: 0.5rem 1rem;
        background: hsl(239, 100%, 27%);
        color: #fff;
        border: none;
    }

    .btn:hover {
        background: hsl(239, 100%, 49%);
    }

</style>
