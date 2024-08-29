<script setup>
import PrimeiroComponente from './components/PrimeiroComponente.vue';
import ComDados from './components/comDados.vue';
import comDadosReativosPrimitivos from './components/comDadosReativosPrimitivos.vue';
import comDadosReativosNaoPrimitivos from './components/comDadosReativosNaoPrimitivos.vue';
import DataBinding from './components/DataBinding.vue';
import ComProps from './components/ComProps.vue';
import EscutaEvento from './components/EscutaEvento.vue';

const borracha = "borracha"
const precoBorracha = 2.50
</script>

<template>
  <header>Vue</header>
  <EscutaEvento/>
  <ComProps :item="borracha" :preco="precoBorracha"/>
  <DataBinding/>
  <comDadosReativosNaoPrimitivos/>
  <comDadosReativosPrimitivos/>
  <ComDados/>
  <PrimeiroComponente/>
</template>

<style scoped>

</style>
