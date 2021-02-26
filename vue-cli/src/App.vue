<template>
  <!-- template root 는 하나의 엘리먼트만 있어야 한다. -->
  <div>
    <app-header></app-header>
  </div>
</template>

<script>
// 컴포넌트 정의한 내용의 파일을 변수에 넣어 참조
import AppHeader from './components/AppHeader.vue';

export default {
  data: function() {
    return {
      str: 'hi'
    }
  },
  components: {
    'app-header' : AppHeader
  }
}
</script>

<style>

</style>