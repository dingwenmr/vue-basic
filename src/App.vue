<template>
  <div id="app">
<!--    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
<!--    <ComputedAndWatch/>-->
<!--      <class-and-style/>-->
<!--      <IfAndShow/>-->
<!--      <list-render/>-->
<!--      <list-render-two/>-->
<!--      <other-instruction/>-->
<!--      <demo/>-->
<!--      <event-deal/>-->
<!--      <demo-filter/>-->
<!--      <transition-and-animate/>-->
<!--      <transition-and-animate-two/>-->
<!--      <transition-and-animate-three/>-->
<!--      <life-circle/>-->
<!--      <father/>-->
<!--      <parent/>-->
      <todo-main/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import ComputedAndWatch from "./components/ComputedAndWatch";
// import ClassAndStyle from "./components/ClassAndStyle";
// import IfAndShow from "./components/IfAndShow";
// import ListRender from "./components/ListRender";
// import ListRenderTwo from "./components/ListRenderTwo";
// import OtherInstruction from "./components/OtherInstruction";
// import Demo from "./components/Demo"
// import EventDeal from "./components/EventDeal";
// import DemoFilter from "./components/DemoFilter";
// import TransitionAndAnimate from "./components/TransitionAndAnimate";
// import TransitionAndAnimateTwo from "./components/TransitionAndAnimateTwo";
// import TransitionAndAnimateThree from "./components/TransitionAndAnimateThree";
// import LifeCircle from "./components/LifeCircle";
// import Father from "./components/props/Father";
// import Parent from "./components/custom-events/Parent";
import TodoMain from "./components/todo/TodoMain";
export default {
  name: 'App',
  components: {
      // Parent,
    // HelloWorld
    // ComputedAndWatch,
    //   ClassAndStyle
    //   IfAndShow
    //   ListRender
    //   ListRenderTwo
    //   OtherInstruction
    //   Demo
    //   EventDeal
    //   DemoFilter
    //   TransitionAndAnimate
    //   TransitionAndAnimateTwo
    //   TransitionAndAnimateThree
    //   LifeCircle
    //   Father
      TodoMain
  }
}
</script>

<style>

</style>
