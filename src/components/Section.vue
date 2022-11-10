<template>
<section class="section-estilo">
    <h1><strong>Cadastre-se</strong></h1>
    <h2>Para melhor personalizar sua tarefa!</h2>
    <input type="text" placeholder="Name">
    <input type="e-mail" placeholder="E-mail">
    <button>
        <strong>Enviar</strong>
    </button>



</section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent ({
    name: "Section"
})

</script>

<style scoped>

.section-estilo {
    display: flex;
    flex-direction: column;
    justify-content: center;
margin-top: 1px;
 
    
}

</style>