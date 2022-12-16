<script setup>
import Dashboard from './components/Dashboard.vue'
import InvestForm from './components/InvestForm.vue'
import Cards from './components/Cards.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <Dashboard msg="Today is the day!" />
    </div>
  </header>

  <main>
    <InvestForm />
  </main>
  <Cards />
</template>
