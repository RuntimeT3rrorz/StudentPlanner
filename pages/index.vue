<template>
  <div class="page">
    <div class="heading">
      <p class="display-4 font-weight-bold white--text">Welcome to Student Planner</p>
      <br>
      <br>
      <p class="display-2 font-weight-bold white--text">Made for students, by students</p>
    </div>

    <br>
    <br>

    <div class="tri-feature">
      <v-row>
        <TriFeature title="Lorem" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed feugiat rhoncus lectus, a facilisis nulla facilisis in. Morbi volutpat tincidunt diam non luctus. Fusce gravida arcu a odio hendrerit eleifend. Nulla iaculis lorem ut massa tincidunt, sit amet tempor nisi auctor. Sed vel tortor nisl. Praesent convallis lectus felis, vel porta massa mattis ut. Nam eget interdum metus. Aenean tincidunt, elit eu dapibus accumsan, tortor augue congue odio, id sodales arcu erat non nunc. Fusce at massa nulla. Cras rhoncus at orci vel gravida. Nam at quam mauris. Pellentesque dapibus massa quam, vel elementum eros laoreet consectetur."></TriFeature>
        <TriFeature title="Lorem" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed feugiat rhoncus lectus, a facilisis nulla facilisis in. Morbi volutpat tincidunt diam non luctus. Fusce gravida arcu a odio hendrerit eleifend. Nulla iaculis lorem ut massa tincidunt, sit amet tempor nisi auctor. Sed vel tortor nisl. Praesent convallis lectus felis, vel porta massa mattis ut. Nam eget interdum metus. Aenean tincidunt, elit eu dapibus accumsan, tortor augue congue odio, id sodales arcu erat non nunc. Fusce at massa nulla. Cras rhoncus at orci vel gravida. Nam at quam mauris. Pellentesque dapibus massa quam, vel elementum eros laoreet consectetur."></TriFeature>
        <TriFeature title="Lorem" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed feugiat rhoncus lectus, a facilisis nulla facilisis in. Morbi volutpat tincidunt diam non luctus. Fusce gravida arcu a odio hendrerit eleifend. Nulla iaculis lorem ut massa tincidunt, sit amet tempor nisi auctor. Sed vel tortor nisl. Praesent convallis lectus felis, vel porta massa mattis ut. Nam eget interdum metus. Aenean tincidunt, elit eu dapibus accumsan, tortor augue congue odio, id sodales arcu erat non nunc. Fusce at massa nulla. Cras rhoncus at orci vel gravida. Nam at quam mauris. Pellentesque dapibus massa quam, vel elementum eros laoreet consectetur."></TriFeature>
      </v-row>
    </div>
  </div>
</template>

<style lang="scss">
  .heading {
    background-color: #03A9F4;
    text-align: center;
    padding: 200px 0;
  }

  .tri-feature {
    margin: 0 32px;
  }
</style>

<script>
import TriFeature from "../components/TriFeature";

export default {
  components: {
    TriFeature
  }
}
</script>
