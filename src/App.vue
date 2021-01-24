<template>
  <div>“喂你好，是尼克陈吗？我是叮咚买菜的送菜员，由于您电话打不通，特意在页面里跟您说一声，您菜到家了。</div>
</template>

<script>
export default {
  setup() {
    const testFunction = () => {
      console.log('滚')
    }

    return {
      testFunction
    }
  }
}
</script>

<style>
  div {
    color: yellowgreen;
  }
</style>