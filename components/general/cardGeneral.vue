<script lang="ts" setup>
const prop = defineProps({
    urlImage:{
        type: String,
        default: 'https://img.freepik.com/foto-gratis/ropa-informal-mujeres-negocios-independientes-usando-videoconferencia-llamada-trabajo-portatil-cliente-lugar-trabajo-sala-estar-casa-feliz-joven-asiatica-relajarse-sentado-escritorio-hacer-trabajo-internet_7861-2448.jpg?w=1060&t=st=1687564975~exp=1687565575~hmac=b46217d904a68063155c00e8b42b23c375c790d05eb104b6bdf0050cc533ae7a',
    },
    categorie: String,
    title: String,
    modality: String,
    hour: String,
    cantidad: String,
    price: String,
    addCart: Boolean
})
</script>

<template>
  <div
    class="max-w-xs bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 text-sm" 
  >
    <a href="#">
      <img
        class="rounded-t-lg"
        :src="urlImage"
        alt=""
      />
    </a>
    
    <div class="p-5">
      <div>
        <p class="text-sm p-2">{{categorie}}</p>
      </div>
      <a href="#">
        <h5
          class="mb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white  overflow-hidden line-clamp-2 "
          >
          <!-- style="-webkit-box-orient: vertical; display: -webkit-box;" -->
          {{title}}
        </h5>
      </a>
      <p class="mb-2 font-normal  text-gray-700 dark:text-gray-400">
        {{modality}}
      </p>
      <div class="flex items-center justify-center space-x-4 mb-2">
        <p class="font-normal text-gray-700 dark:text-gray-400">
        {{cantidad}}
        </p>
        <p class="font-normal text-gray-700 dark:text-gray-400">
        {{hour}}
        </p>
      </div>

      <div class="mb-2">
        <p class="font-bold">s/{{price}}</p>
      </div>
    </div>
  </div>
</template>
