<template>
  <div id="dashboard">
    <section>
      <div class="col1">
        <div class="profile">
          <h5>n</h5>
          <p></p>
          <div class="create-post">
            <p>create a post</p>
            <form @submit.prevent>
              <textarea></textarea>
              <button class="button">post</button>
            </form>
          </div>
        </div>
      </div>
      <div class="col2">
        <div>
          <p class="no-results">There are currently no posts</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
  data () {
    return {

    }
  },
  computed: {
    ...mapState(['userProfile'])
  },
  methods: {

  }
}
</script>

<style lang="scss" scoped>
</style>