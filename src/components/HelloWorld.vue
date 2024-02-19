<template>
  <div>
    <img :src="require('../assets/img/gatito.jpg')" alt="gatito" style="width: 200px; height: auto; "> 
  <h1>info personal: {{ info }}</h1>
  </div>
</template>

<script>
export default{
  data (){
    return{
      info: 'Alejandra Lizeth, 20975, 5A'
    }
  }
}
</script>