<template>
  <main class="main">
    <section class="products">
      <h1 class="main__title">Наша продукция</h1>

      <ul class="filter">
        <li class="filter__item">
          <span class="filter__item-value">1л</span>

          <span class="filter__item-container">Бутылка</span>
        </li>
        <li class="filter__item">
          <span class="filter__item-value">1л</span>

          <span class="filter__item-container">Бутылка</span>
        </li>
        <li class="filter__item">
          <span class="filter__item-value">1л</span>

          <span class="filter__item-container">Бутылка</span>
        </li>
        <li class="filter__item">
          <span class="filter__item-value">1л</span>

          <span class="filter__item-container">Бутылка</span>
        </li>
      </ul>
    </section>

    <section class="slider">
      <hooper>
        <slide> slide 1 </slide>
        <slide> slide 2 </slide>
      </hooper>
    </section>
  </main>
</template>

<script>
import { Hooper, Slide } from 'hooper';
import 'hooper/dist/hooper.css';
export default {
  name: 'Product',

  components: {
    Hooper,
    Slide,
  },

  head: {
    title: 'Продукты',
  },
};
</script>

<style scoped></style>
