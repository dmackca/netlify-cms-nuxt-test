<template>
  <div>
      <b>this is some component</b>
      <pre>
          Foo:
          ---
          {{ foo }}
          ---
          Baz:
          ---
          {{ baz }}
      </pre>
  </div>
</template>

<script>
export default {
    props: ['foo', 'baz']
}
</script>

<style>

</style>
