<template>
  <header>
    <div class="header-container">
      <router-link to="/">
          <img src="../assets/logo.png" alt="logo" class="logo">
      </router-link>
      <div class="links-container">
        <router-link to="/about">Teams</router-link>
        <router-link to="/about">Locations</router-link>
        <router-link to="/about">Life at Google</router-link>
        <router-link to="/about">How we hire</router-link>
        <router-link to="/about">Students</router-link>
        <router-link to="/about">Jobs</router-link>
      </div>
    </div>
    <div class="button-container">
      <BaseButton title="Sign in"/>
    </div>
  </header>
</template>
<script>
import "./scss/_app_header.scss";
import BaseButton from '../components/BaseButton.vue'

export default {
  name : "AppHeader",
  components :{
    BaseButton
  }
}
</script>
