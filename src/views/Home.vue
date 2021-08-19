<template>
  <div class="home">
    <CheckForm/>
  </div>
</template>

<script>
// @ is an alias to /src
import  CheckForm from '@/components/CheckForm.vue';

export default {
  name: 'Home',
  components: {
    CheckForm
  }
}
</script>
