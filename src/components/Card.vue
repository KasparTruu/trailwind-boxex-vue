<template>
  <div class="card relative p-6 rounded-lg shadow-lg  flex flex-col justify-between" :class="bgColor">
    <h2 class="text-xl font-bold mb-2">{{ title }}</h2>
    <p class="text-gray-700">{{ description }}</p>
    <div class="shape absolute top-4 right-4 w-8 h-8">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2L2 7l10 5 10-5-10-5z" />
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2 17l10 5 10-5M2 12l10 5 10-5" />
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
    bgColor: {
      type: String,
      default: 'bg-purple-200',
    },
  },
}
</script>

<style scoped>
.shape {
  position: absolute;
}
</style>
