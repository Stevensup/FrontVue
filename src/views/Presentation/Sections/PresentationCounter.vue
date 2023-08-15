<script setup>
import DefaultCounterCard from "../../../examples/cards/counterCards/DefaultCounterCard.vue";
</script>

<template>
  <section class="pt-3 pb-4" id="count-stats">
    <div class="container">
      <div class="row">
        <div class="col-lg-9 z-index-2 border-radius-xl mx-auto py-3">
          <div class="row">
            <div class="col-md-4 position-relative">
              <DefaultCounterCard
                color="danger"
                title="Remodelaciones"
                description="Contador que muestra un total de 70 remodelaciones exitosas. ¡Actualiza y renueva tus espacios con éxito!"
                :count="70"
                suffix="+"
                :duration="3000"
                divider="vertical"
              />
            </div>
            <div class="col-md-4 position-relative">
              <DefaultCounterCard
                color="danger"
                title="Diseño"
                description="Conoce 50 diseños impresionantes. Desde botones hasta alertas, todo está cubierto en tu proyecto creativo."
                :count="15"
                suffix="+"
                :duration="3000"
                divider="vertical"
              />
            </div>
            <div class="col-md-4">
              <DefaultCounterCard
                color="danger"
                title="Mejoras Exitosas"
                description="Descubre más de 100 mejoras exitosas implementadas. Desde pequeños cambios hasta grandes logros, cada paso es un éxito hacia el progreso."
                :count="4"
                :duration="3000"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
