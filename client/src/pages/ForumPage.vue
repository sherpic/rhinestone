<script>
import Forum from './../components/Forum/Forum'
export default {
  components: {
    Forum
  }
}
</script>

<template>
  <div id="forum-wrapper">
    <div class="row">
      <div class="col-md-8">
        <h1 class="page-title">Forum</h1>
      </div>
    </div>
    <div class="row">
      <div class="col-md-8">
        <router-view></router-view>
      </div>
      <div class="col-md-4">
        <p>This is where Forum Sidebar will come</p>
      </div>
    </div>
  </div>
</template>
