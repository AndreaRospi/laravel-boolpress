<template>
  <header>
    <h2>I'm the header</h2>
    <a href="/admin/home"><button>Area Riservata</button></a>
    <nav>
      <ul>
        <li>
          <router-link :to="{ name: 'home' }">Home</router-link>
        </li>
        <li>
          <router-link router-link :to="{ name: 'about' }"
            >Chi Siamo</router-link
          >
        </li>
        <li>
          <router-link router-link :to="{ name: 'categories' }"
            >Categorie</router-link
          >
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
</style>