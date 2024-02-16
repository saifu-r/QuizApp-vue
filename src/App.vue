<template>
  <div class="App">
    <Condition/>
    
  </div>

</template>

<script lang="ts">
import { defineComponent} from 'vue';

import Condition from './components/Condition.vue'


export default defineComponent({
  name: 'App',
  components: {Condition}
  
});
</script>

<style>


</style>
