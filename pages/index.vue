<template>
  <Tutorial />
</template>

<script>
export default {
  name: 'IndexPage',
  mounted () {
    const x = { person: { real: true, name: 'bob' } }
    if (x?.person?.real) {
      console.log(x.person.name)
    }
  },
}
</script>
