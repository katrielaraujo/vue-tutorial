<template>
    <div class="componente">
        <h1>Componente com Data Binding</h1>
        <P>{{ valor }}</P>
        <!-- <input type="text" v-bind:value="valor"></input> -->
         <input type="text" v-model="valor"></input>
    </div>
</template>

<script setup>
import {ref} from "vue"
const valor = ref("Vue é muito legal")
</script>