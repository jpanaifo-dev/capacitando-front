<template>
    <div class="">
        <div class="grid grid-cols-2 gap-4">
    <div class="">
      <div class="mb-4">
        <p class="text-5xl font-bold">Hola, nombre de perfil</p>
      </div>
      <div class="mb-4 flex flex-col gap-3">
        <p class="text-md font-ligth">
          Bienvenido a la plataforma Capacitandome, aquí encontrarás recursos que te
          ayudarán en tu adaptación y adquirir conocimientos, así como tu egreso
          efectivo y consolidación de tu proyecto profesional.
        </p>
        <p class="text-md font-semibold">
          Mira el siguiente video , el cual te explicará que contenidos verás
          durante este semestre.
        </p>
      </div>
      <div>
        <button
          type="button"
          class="text-white bg-gradient-to-r from-purple-500 via-purple-600 to-purple-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-purple-300 dark:focus:ring-purple-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2"
        >
          Purple
        </button>
      </div>
    </div>

    <div>
      <video class="h-80" controls>
        <source src="/docs/videos/flowbite.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
    </div>
</template>
