<template>
<main class="columns is-gapless is-multiline">
  <div class="column is-one-quarter">
    <BarraLateral/>
   
  </div>
  <div class="column is trhee-quarter">
    <FormularioPrincipal/>
<div class="lista">
  <Tarefa/>
  <Tarefa/>
  <Tarefa/>
  <Tarefa/>

</div>
    
  </div>
</main>

</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import FormularioPrincipal from './components/FormularioPrincipal.vue';
import Tarefa from './components/Tarefa.vue';
import ITarefa from './interfaces/ITarefa';

export default defineComponent({
  name: 'App',

  components: {
    BarraLateral,
    FormularioPrincipal,
    Tarefa,
},
data () {
  return {
    tarefas: [] as ITarefa[]
  }
}
 
});
</script>

<style>
main {
  display: flex;
}

.lista {
  padding: 1.25rem;
}

</style>
