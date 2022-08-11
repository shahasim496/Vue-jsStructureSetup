
<template>

<WelcomeNavbar />


  <router-view />

  <AppFooter />

</template>

<script>

import WelcomeNavbar from "./components/WelcomeNavbar.vue";
import AppFooter from "./components/AppFooter.vue";


 export default {

    components: { WelcomeNavbar, AppFooter }
}
</script>