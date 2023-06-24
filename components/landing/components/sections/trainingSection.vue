<template>
  <div class="text-center flex flex-col items-center">
    <div class="mb-1">
      <div><p class="text-sm">CAPACITACIONES</p></div>
      <div><p class="text-3xl mb-6">Nuestras capacitaciones</p></div>
    </div>
    <div class="grid grid-cols-3 gap-4">
      <GeneralCardGeneral
        v-for="course in courses"
        :key="course.id"
        :categorie="course.categoria"
        :title="course.nombreCurso"
        :modality="course.modalidad"
        :cantidad="course.cupos"
        :hour="course.horas"
        :price="course.precio"
      />
    </div>
    <div></div>
  </div>
</template>

<script lang="ts" setup>
const courses = [
  {
    id: 1,
    categoria: "INVESTIGACION",
    nombreCurso: "Cambio Climático en la Amazonía",
    modalidad: "Modalidad virtual",
    cupos: "10 cupos",
    horas: "20 horas",
    precio: "100",
  },
  {
    id: 2,
    categoria: "INVESTIGACION",
    nombreCurso: "Inteligencia Artificial",
    modalidad: "Modalidad virtual",
    cupos: "10 cupos",
    horas: "20 horas",
    precio: "100",
  },
  {
    id: 3,
    categoria: "INVESTIGACION",
    nombreCurso: "Inteligencia Artificial",
    modalidad: "Modalidad virtual",
    cupos: "10 cupos",
    horas: "20 horas",
    precio: "100",
  },
  {
    id: 4,
    categoria: "INVESTIGACION",
    nombreCurso: "Inteligencia Artificial",
    modalidad: "Modalidad virtual",
    cupos: "10 cupos",
    horas: "20 horas",
    precio: "100",
  },
  {
    id: 5,
    categoria: "INVESTIGACION",
    nombreCurso: "Inteligencia Artificial",
    modalidad: "Modalidad virtual",
    cupos: "10 cupos",
    horas: "20 horas",
    precio: "100",
  },
];
</script>
