<template>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <h2 style="color:#000 !important;">KANBAN-APP</h2>
        <hr>
        <!-- BACKLOG -->
        <div class="col-md-3">
          <div class="row">
            <div class="col-sm-12">
              <div class="thumbnail" >
                <h1 style="background-color:#ccdef9 ;">BACKLOG</h1>
              </div>
            </div>
          </div>
        </div>
        <!-- TODO -->
        <div class="col-md-3">
          <div class="row">
            <div class="col-sm-12">
              <div class="thumbnail">
                <h1 style="background-color:#ccdef9;">TO-DO</h1>
              </div>
            </div>
          </div>
        </div>
        <!-- DOING -->
        <div class="col-md-3">
          <div class="row">
            <div class="col-sm-12">
              <div class="thumbnail">
                <h1 style="background-color:#ccdef9;">DOING</h1>
              </div>
            </div>
          </div>
        </div>
        <!-- DONE -->
        <div class="col-md-3">
          <div class="row">
            <div class="col-sm-12">
              <div class="thumbnail">
                <h1 style="background-color:#ccdef9;">DONE</h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
