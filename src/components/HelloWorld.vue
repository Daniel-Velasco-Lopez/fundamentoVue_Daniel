<script setup>
/// Importación del Card Principal
import CardPrincipal from './CardPrincipal.vue';
//Importación del 1er card
import Card from './Card.vue';
//metodos
</script>

<template>
    <div class="container">
        <h1 class="text-center">REFACCIONARIA TIMÓN</h1>
        <!--INICIO DEL PRIMER ROW-->
        <card-principal/>
        <!--FIN DEL PRIMER ROW-->

        <!--Llamamos al componente importado-->
        <card/>
        <!--Fin del llamado al componente importado-->
    </div>
</template>

<style scoped>

</style>
