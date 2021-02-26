<template>
  <!-- template root 는 하나의 엘리먼트만 있어야 한다. -->
  <div>
    {{ str }}
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      str: 'hi'
    }
  }
}
</script>

<style>

</style>