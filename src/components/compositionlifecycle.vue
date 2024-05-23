<template>
<h1>This is composotion Api life cycle hooks</h1>
</template>

<script>

import{onBeforeMount,onMounted,onBeforeUpdate,onUpdated,onBeforeUnmount,onUnmounted} from 'vue'

export default {
name:'composition-life-cycle',
setup(){
onBeforeMount(()=>{
    console.log("Composition  onbeforeMount()")
  })
  onMounted(()=> {
    console.log("Composition onmounted()")
  })
  onBeforeUpdate(()=>{
    console.log("Composition onbeforeUpdate()")
  })
  onUpdated(() =>{
    console.log("Composition onupdated()")
  })
  onBeforeUnmount(()=> {
    console.log("Composition onbeforeUnmount()")
  })
  onUnmounted(()=> {
    console.log("Composition onunmounted()")
  })
}
// onbeforeCreate() {
//     console.log("Parent beforeCreate()");
//   },
//   oncreated() {
//     console.log("Parent created()");
//   },
  
}
</script>

<style>

</style>