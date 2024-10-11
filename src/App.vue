<template>
  <div class="container mx-auto p-12">
    <div class="grid grid-cols-2 gap-10">
        <div class="grid w-full">
          <div class="flex gap-10 mt-10 ">
            <div>
              <Card 
                title="Engagement"
                description="Develop your sense of belonging and active involvement in meaningful activities."
                bgColor="bg-blue-200"
                class=""
                
              />
            </div>

            <div>
              <Card 
                title="Engagement"
                description="Develop your sense of belonging and active involvement in meaningful activities."
                bgColor="bg-pink-200" 
              />
            </div>
          </div>

          <div>
            <Card 
              title="Engagement"
              description="Develop your sense of belonging and active involvement in meaningful activities."
              bgColor="bg-yellow-200" 
              class="h-[400px] mt-10"
            />
          </div>
      </div>

      <div class="grid grid-cols-1 w-full">
          <div class="mb-10">
            <Card 
              title="Engagement"
              description="Develop your sense of belonging and active involvement in meaningful activities."
              bgColor="bg-purple-200" 
              class="h-[400px] mt-10"
            />
          </div>

          <div class="flex gap-10" >
            <div>
              <Card 
                title="Engagement"
                description="Develop your sense of belonging and active involvement in meaningful activities."
                bgColor="bg-gray-200"
                class=""
                
              />
            </div>

            <div>
              <Card 
                title="Engagement"
                description="Develop your sense of belonging and active involvement in meaningful activities."
                bgColor="bg-red-200" 
              />
            </div>
          </div>
      </div>


    </div>
  </div>
</template>

<script>
import Card from './components/Card.vue'; // Import the Card component

export default {
  components: {
    Card, // Register the Card component
  },
}
</script>

<style scoped>
.container {
  max-width: 1200px;
}
</style>
