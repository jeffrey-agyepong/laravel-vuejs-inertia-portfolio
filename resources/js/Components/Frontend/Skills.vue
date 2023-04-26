<script setup>
defineProps({
  skills: Object,
});
</script>
<template>
  <!-- <section class="bg-light-tail-100 dark:bg-dark-navy-500 py-16">
    <div class="container mx-auto">
      <h2 class="section-title text-center">Skills</h2>
      <div class="grid grid-cols-8 md:grid-flow-col">
        <div
          class="flex items-center justify-center"
          v-for="skill in skills.data"
          :key="skill.id"
        >
          <img :src="skill.image" :alt="skill.name" class="lg:h-20" />
        </div>
      </div>
    </div>
  </section> -->
  <section class="bg-light-tail-100 dark:bg-dark-navy-500 py-16">
  <div class="container mx-auto">
    <h2 class="section-title text-center">Skills</h2>
    <div class="flex flex-wrap md:flex-nowrap lg:flex-nowrap justify-center -mx-4">
      <div class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 px-4 my-4" v-for="skill in skills.data" :key="skill.id">
        <img :src="skill.image" :alt="skill.name" class="h-auto mx-auto max-w-full" style="max-width: 150px;" />
      </div>
    </div>
  </div>
</section>


</template>