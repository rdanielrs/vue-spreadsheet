<script setup lang="ts">
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
/*import SignIn from './views/SignIn.vue';
import Login from './components/Onboarding/Login.vue'*/
import router from './router';
</script>

<!--<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>-->

<!--<template>
  <Header />
  <Login />

</template>-->

<template>
  <!--<Header/>-->
  <Header/>
  <RouterView/>
</template>


<style>
  body {
    /*background: #070707;*/
    /*background: #1B1F3B;*/
    background: #071013;
  }

</style>


