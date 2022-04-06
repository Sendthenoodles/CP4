<template>
<div>
  <Admin v-if="user && user.role === 'admin'" />

</div>
</template>


<script>
import axios from 'axios';
import HomePage from '@/components/HomePage.vue'


export default {
  name: 'HomePage',
  components: {
    HomePage,
  },
  computed: {
    user() {
      return this.$root.$data.user;
    }
  },
   async created() {
    try {
      let response = await axios.get('/api/users');
      this.$root.$data.user = response.data.user;
    } catch (error) {
      this.$root.$data.user = null;
    }
  },
}
</script>

