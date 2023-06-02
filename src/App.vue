<script setup>
import { reactive } from 'vue';

function adicao() {
  const { numeroA, numeroB } = estado;
  return numeroA + numeroB;
}

function subtracao() {
  const { numeroA, numeroB } = estado;
  return numeroA - numeroB;
}

function multiplicacao() {
  const { numeroA, numeroB } = estado;
  return numeroA * numeroB;
}

function divisao() {
  const { numeroA, numeroB } = estado;
  return numeroA / numeroB;
}

function resultadoOperacao() {

}

</script>

<template>
  <div class="container">
    <h1>Calculadora Aritimética</h1>
    <h3>Digite os números e veja o resultado aparecer</h3>
    <input type="number">Numéro A
    <input type="number">Número B
    <select>
      <option value="Adiçãos">Adição</option>
      <option value="Subtração">Subtração</option>
      <option value="Multiplicação">Multiplicação</option>
      <option value="Divisão">Divisão</option>
    </select>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
}

</style>
