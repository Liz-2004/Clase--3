<template>
  <div>
    <img :src="require('../assets/img/nata.jpg')" alt="nata" style="width: 200px; height: auto; "> 
  <h1>info personal: {{ info }}</h1>
  </div>
</template>

<script>
export default{
  data (){
    return{
      info: 'Angel Emmanuel Cerda, 20974, 5A'
    }
  }
}
</script>