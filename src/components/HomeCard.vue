<script setup>
import Card from "./Card.vue";
</script>
<template>
  <section class="py-4">
    <div class="container-xl lg:container m-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 p-4 rounded-lg">
        <Card
          title="For Employers"
          description="List your job to find the perfect developer for the role"
        />
        <Card
          title="For developers"
          description="Browse our Vue jobs and start your career today"
          bgColor="bg-green-100"
        />
      </div>
    </div>
  </section>
</template>
