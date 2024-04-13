import router from './router';
<template>
  <header>
    <router-link :to="{ name: 'home' }">Home</router-link> |
    <router-link to="/categorias">Categorias</router-link> |
    <router-link to="/cores">cores</router-link> |
    <router-link to="/marcas">marcas</router-link> |
    <router-link to="/acessorios">acessorios</router-link> 
  </header>
  <main>
    <RouterView />
  </main>
</template>
