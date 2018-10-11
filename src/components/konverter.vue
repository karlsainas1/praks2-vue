<template>
  <div class="hello">
   <h1>Konverter</h1>
   <h4>sisesta kaal kilogrammides:</h4>
    <input type="number" v-model="kg" min=0>
    
     <table>
        <tr>
        <td>Grammid</td>
        <td> {{`${kg*1000}g`}} </td>
    </tr>
    <tr>
        <td>Naelad</td>
        <td></td>
    </tr>
    <tr>
        <td>Untsid</td>
        <td></td>
    </tr>
        
    </table>
      </div>
</template>

<script>
export default {
  name: 'konverter',
  data(){
      return{
          kg:0
          
      }
  },
    methods:{
      
        
        
        
    },
    computed: {
        
                
        }
    }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->


<style scoped>

</style>
