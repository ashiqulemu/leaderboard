<template>
  <div >
    <LeaderBoard></LeaderBoard>
  </div>
</template>

<script>
// @ is an alias to /src
  import LeaderBoard from '@/components/LeaderBoard.vue';

export default {
  name: 'HomeView',
  components: {
    LeaderBoard,
  }
}
</script>
