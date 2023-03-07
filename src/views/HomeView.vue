<template>
  <P>{{name}}</P>
</template>

<script>
// @ is an alias to /src

import {reactive,toRefs} from "vue"
export default {
  name: 'home',
  setup(){
    const data = reactive({
      name:"小红",
      阿哥:20,
      info:"<i>斜体</i>"
    })
    return data
  }
}
</script>
