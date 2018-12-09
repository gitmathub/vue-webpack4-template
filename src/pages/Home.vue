<template>
  <div class="full-width center-content">
    <h1>Vuejs lab</h1>
    <image-upload />
  </div>
</template>

<script>
import WelcomeMessage from "components/Home/WelcomeMessage"
import imageUpload from "components/image-upload"

export default {
  components: {
    WelcomeMessage,
    imageUpload
  }
}
</script>
