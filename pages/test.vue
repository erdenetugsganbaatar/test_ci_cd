<template>
  <div>
    <h1>Test page</h1>
    <p>{{ members }}</p>
  </div>
</template>

<script>
import members from '../localDB/members.json'
export default {
  data() {
    return {
      members,
    }
  },
}
</script>
