<script setup>
import PrimeiroComponente from './components/PrimeiroComponente.vue';
import ComDados from './components/comDados.vue';
import comDadosReativosPrimitivos from './components/comDadosReativosPrimitivos.vue';
import comDadosReativosNaoPrimitivos from './components/comDadosReativosNaoPrimitivos.vue';
import DataBinding from './components/DataBinding.vue';
</script>

<template>
  <header>Vue</header>
  <DataBinding/>
  <comDadosReativosNaoPrimitivos/>
  <comDadosReativosPrimitivos/>
  <ComDados/>
  <PrimeiroComponente/>
</template>

<style scoped>

</style>
