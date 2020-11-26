<script>
  export let level = undefined;
  export let width = 24;
  export let offset = 0;
  $: indentation = (level || 0) * width + offset;
</script>
<div indent={indentation || 0} style="width: {indentation}px"/>
<style>
  div {
    display: block;
    min-height: 1px;
  }
</style>