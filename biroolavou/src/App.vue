<script setup>
import Olavou from './components/olavou.vue'
import Resposta from './components/Resposta.vue'
</script>

<template>
  <div class="estrutura">
    <div class="pergunta">
      <Olavou />
    </div>
    <br>
    <div class="resposta">
      <Resposta />
    </div>
  </div>
  <footer>
    <h6>
      <a target="_blank" href="https://www.youtube.com/watch?v=402CQ8yO4ho">A gente lamenta todos os mortos, mas é o destino do mundo </a></h6>
    <p>Done by AneS<br>
     <a target="_blank" href="https://github.com/AneS279">GitHub</a></p>
  </footer>
</template>

<style scoped>
.estrutura {
    display: flex;
    flex-direction: column;
    align-items: center;
}
footer{
  margin-left: -10%;
}
</style>
