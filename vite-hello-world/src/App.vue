
import Apptitle from './components/apptitle.vue';

<template>

  <Apptitle/>  

</template>
<script>
import Apptitle from './components/apptitle.vue';
import apptitle from './components/apptitle.vue';
export default{
    name: "App",
    components: apptitle,
    components: { Apptitle }
}</script>

<style lang="css" scoped></style>