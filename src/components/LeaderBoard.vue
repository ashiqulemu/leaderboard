<template>
  <div class="leaderboard">
    <div class="title">
      winarena
    </div>
    <div class="board-container">
      <div class="items" v-for="(item,idx) in leaderboard" :key="idx">
        <div class="status">
          <div class="position">{{idx + 1}}</div>
          <div class="user">{{item.user}}</div>
        </div>
        <div class="point">
          {{item.point}}
        </div>
      </div>
     
    </div>
  </div>
</template>

<script>
export default {

  data(){
    return{
      leaderboard:[
        { 
          user:'Paul C. Ramos',
          point:5000,
        },
        {  
          user:'Derrick L. Thoman',
          point:4985,
        },
        {  
          user:'Kelsey T. Donovan',
          point:4985,
        },
        {  
          user:'Jack L. Gregory',
          point:4985,
        },
        {  
          user:'Mary R. Mercado',
          point:4985,
        },
        {  
          user:'Theresa N. Maki',
          point:4985,
        },
        {  
          user:'Jack L. Gregory',
          point:4985,
        },
        {  
          user:'8 James R. Stokes',
          point:4985,
        },
        {  
          user:'9 David B. Rodriguez',
          point:4985,
        },
        {  
          user:'Annette R. Allen',
          point:4985,
        },
        {  
          user:'Kelsey T. Donovan',
          point:4985,
        },
        {  
          user:'Jack L. Gregory',
          point:4985,
        },
        {  
          user:'Mary R. Mercado',
          point:4985,
        },
        {  
          user:'Theresa N. Maki',
          point:4985,
        },
       
      ]
    }
  },

}
</script>
 
