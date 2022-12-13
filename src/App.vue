<template>
<Header />
  <section>
    <div class="container">
      <div class="flex justify-center flex-wrap max-w-screen-lg">
        <div class=" bg-white m-2 h-96 w-64">
          <div
            class="bg-[url('/images/132381386G1.webp')] w-64 h-64 bg-no-repeat"
          ></div>
          <p>{{noteBook1.title}}</p>
          <p>{{noteBook1.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white m-2 h-96 w-64">
          <div
            class="bg-[url('/images/132381386G1.webp')] w-64 h-64 bg-no-repeat"
          ></div>
          <p>{{noteBook2.title}}</p>
          <p>{{noteBook2.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white m-2 h-96 w-64">
          <div class="bg-[url('/images/3.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{noteBook3.title}}</p>
          <p>{{noteBook3.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white m-2 h-96 w-64">
          <div class="bg-[url('/images/4.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{noteBook4.title}}</p>
          <p>{{noteBook4.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white m-2 h-96 w-64">
          <div class="bg-[url('/images/5.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{noteBook5.title}}</p>
          <p>{{noteBook5.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white m-2 h-96 w-64">
          <div class="bg-[url('/images/6.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{noteBook6.title}}</p>
          <p>{{noteBook6.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-8 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white m-2 h-96 w-64">
          <div class="bg-[url('/images/7.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{smartPhone1.title}}</p>
          <p>{{smartPhone1.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white  m-2 h-96 w-64">
          <div class="bg-[url('/images/8.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{smartPhone2.title}}</p>
          <p>{{smartPhone2.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white  m-2 h-96 w-64">
          <div class="bg-[url('/images/9.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{smartPhone3.title}}</p>
          <p>{{smartPhone3.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white  m-2 h-96 w-64">
          <div class="bg-[url('/images/10.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{smartPhone4.title}}</p>
          <p>{{smartPhone4.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white  m-2 h-96 w-64">
          <div class="bg-[url('/images/11.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{smartPhone5.title}}</p>
          <p>{{smartPhone5.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-2 ml-2">Add to Cart</button>
        </div>
        <div class="bg-white  m-2 h-96 w-64">
          <div class="bg-[url('/images/12.webp')] w-64 h-64 bg-no-repeat"></div>
          <p>{{smartPhone6.title}}</p>
          <p>{{smartPhone6.price}}</p>
          <button class="h-10 w-60 bg-green-500 text-white mt-8 ml-2">Add to Cart</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from "vue";

import Header from "./components/Header.vue";

const noteBook1 = ref({
  title: "Notebook Lenovo Ideapad 320 Intel® Core i5-7200u 8GB",
  price: "R$ 2259, 00",
});

const noteBook2 = ref({
  title: "Notebook Dell Inspiron i15-3567-A30P Intel Core 7ª i5 4GB",
  price: "R$ 2284, 00",
});

const noteBook3 = ref({
  title: "Notebook Samsung Essentials E21 Intel Celeron Dual Core",
  price: "R$ 1490, 00",
});

const noteBook4 = ref({
  title: "Notebook Samsung Expert X22 Intel Core 7 i5 8GB",
  price: "R$ 2307, 00",
});

const noteBook5 = ref({
  title: "Notebook VAIO Fit 15S B1211B Intel Core i5 4GB",
  price: "R$ 2599, 00",
});

const noteBook6 = ref({
  title: "Notebook Dell Alienware - i7 16GB",
  price: "R$ 14000, 00",
});

const smartPhone1 = ref({
  title: "Smartphone Xiaomi Mi A1 dual Android one 7.1",
  price: "R$ 1199, 00",
});

const smartPhone2 = ref({
  title: "Smartphone Moto G 5S Dual Chip Android 7.0",
  price: "R$ 929, 00",
});

const smartPhone3 = ref({
  title: 'iPhone 8 Dourado 64GB Tela 4.7" IOS 11',
  price: "R$ 3949, 00",
});

const smartPhone4 = ref({
  title: "Smartphone Samsung Galaxy S7 Edge",
  price: "R$ 1943, 00",
});

const smartPhone5 = ref({
  title: "Smartphone Motorola Moto G6 Plus",
  price: "R$ 1699, 00",
});

const smartPhone6 = ref({
  title: "Smartphone Motorola Moto Z3 Play",
  price: "R$ 2999, 00",
});
</script>

<style></style>
