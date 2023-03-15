<template>
  <div>
    <Header/>
    <nuxt/>
    <transition name="fade">
      <Alert v-if="$store.state.ui.alertData.state === true"/>
    </transition>
    <Footer/>
  </div>
</template>

<script>
import Alert from "~/components/Alert.vue"
import Header from "~/components/layouts/header.vue"
import Footer from '~/components/layouts/footer.vue'
export default {
  name: "layout",
  components: {
    Alert,
    Header,
    Footer
  }
}
</script>