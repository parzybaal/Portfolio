<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import NavBar from './components/NavBar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Work from './components/Work.vue'
import Social from './components/Social.vue'
import Email from './components/Email.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
import 'animate.css'
import 'aos/dist/aos.css'

</script>

<template>
  <div id="main" :class="dark ? 'dark' : 'ligth'">
    <div class="bg-slate-100 dark:bg-[#0a192f]">
      <NavBar />
      <Social />
      <Email />
      <Home />
      <About />
      <Skills />
      <Work />
      <Contact />
      <Footer />
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
import AOS from 'aos'

if(!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches){ localStorage.theme = 'dark' }
else if(!('theme' in localStorage)){ localStorage.theme = 'light' }

if(!('lang' in localStorage) && navigator.language.includes('es')){ localStorage.lang = 'es' }
else if(!('lang' in localStorage)){ localStorage.lang = 'en' }

export default {
  computed: {
    ...mapGetters(['dark'])
  }, 
  mounted() {
    AOS.init({
      duration: 1000,
      easing: 'ease-in-out',
      once: true,
      throttleDelay: 400
    })
  }
}
</script>
