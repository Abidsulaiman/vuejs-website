<template>
  <Navbar/>
  <Header/>
  <Download/>
  <Features/>
  <Cta/>
  <Contact/>
  <Footer/>
</template>

<script>
import Navbar from './components/Navbar'
import Header from './components/Header'
import Download from './components/Download'
import Features from './components/Features'
import Cta from './components/Cta'
import Contact from './components/Contact'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    Download,
    Features,
    Cta,
    Contact,
    Footer
  }
}
</script>

<style>

</style>
