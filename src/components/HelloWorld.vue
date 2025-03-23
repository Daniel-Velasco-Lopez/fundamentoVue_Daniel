<script setup>
import Card from './Card.vue';
//metodos
</script>

<template>
    <div class="container">
        <h1 class="text-center">REFACCIONARIA TIMÓN</h1>
        <!--INICIO DEL PRIMER ROW-->
        <di class="row"> 
            <div class="col-md-6">
                <div class="card">
                    <h6>Motocicletas</h6>
                    <div class="card-header">

                    </div>
                    <div class="card-body">
                        <p class="card-text">Kawasaki Ninja H2R: La moto más rápida del mundo con su impresionante motor de 4 cilindros de 998 cc.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card">
                    <h6>Cuatrimotos</h6>
                    <div class="card-header">

                    </div>
                    <div class="card-body">
                        <p class="card-text">RAPTOR 700R SE - Yamaha Motos.</p>
                    </div>
                </div>
            </div>
        </di>
        <!--FIN DEL PRIMER ROW-->

        <!--Llamamos al componente importado-->
        <card/>
        <!--Fin del llamado al componente importado-->

        <card/>
    </div>
</template>

<style scoped>

</style>
