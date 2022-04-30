<template>
<div class="app">
  <Nuxt keep-alive />
</div>
</template>

<script>
export default{
  data(){
    return{
      movies: [],
       
    }
  },
  methods:{
    async getMovies(){
      const data = axios.get()
    }
  }
}
</script>