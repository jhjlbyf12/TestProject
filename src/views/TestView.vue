<template>	
    <div>
        <H1>Тестовая страница</H1>

        <img alt="Vue logo" src="../assets/logo.png">

        <HelloWorld></HelloWorld>   // добавить для отображения на странице

    </div>
</template>

<script>

import HelloWorld from '../components/HelloWorld.vue';


export default {
  name: 'TestView',

  components: {HelloWorld},   ///прописываем дочерний компонент

  props: {
    msg: String
  }
}
</script>