<template>

    <div>

        <H1>Корзина</H1>

        <BattonTopP></BattonTopP>

    </div>

</template>

<script>

import BattonTopP from '../components/BattonTopP.vue'


export default {
  name: 'КорзинаtView',

  components:{BattonTopP},
  props: {
    msg: String
  }
}
</script>

