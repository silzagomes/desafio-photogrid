<template>
<div id="app">
  <NovoComponente/>
  </div>
</template>

<script>
import NovoComponente from './components/NovoComponente'
export default {
  name: 'App',
  components:{
    NovoComponente
  }
};
</script>

<style>
.novo-componente{
 display: flex;
        justify-content:flex-start;
        align-items: left;
        text-align:left;
        
}
</style>