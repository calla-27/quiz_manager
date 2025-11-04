<template>
  <div id="app">
    <!-- <user-view></user-view> -->
    <!-- <question-view></question-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
//import UserView from './views/element/UserView.vue';
//import QuestionView from './views/element/QuestionView.vue';

//import TestButton from './views/element/TestButton.vue';

export default{
  //components:{ QuestionView},
  data(){
    return{
      message:"hello vue",
    };
    
  },
  methods:{},
};
</script>

<style>
#htitle{
  color:rgb(130, 171, 198);
}
#inputnumber{
  margin-top:20px
}
</style>
