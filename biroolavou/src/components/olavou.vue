<script setup>
  var girias = [
    'deixou de tankar',
    'foi de berço',
    'foi de Jacksons Five',
    'foi de comes e bebes',
    'foi de base',
    'bateu as caçoleta',
    'olavou',
    'bateu as botas',
    'despachou o beco',
    'abotoou o paletó',
    'comeu capim pela raiz',
    'vestiu o pijama de madeira',
    'virou presunto'
  ];

function getRandomInt(max) {
  return Math.floor(Math.random() * max);
  }
  var random = getRandomInt(girias.length)
</script>

<template>
  <div class="greetings">
    <h1>O Capitão {{girias[random]}}?</h1>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}
</style>
