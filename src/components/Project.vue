<template>
<div class="container">
  <div class="project-container">
      <div class="red box"></div>
      <div class="blue box"></div>
      <div class="blue box"></div>
      <div class="blue box"></div>
      <div class="blue box"></div>
      <div class="yellow box"></div>
      <div class="yellow box"></div>
  </div>
  <div class="task-container">
    <h2>Task Description</h2>
    <p>Style boxes in container on the left so they match the pattern below:</p>
    <div>
      <img alt="anser image" src="../assets/answer-layout.png">
    </div>
    <div>
      <p>Some flex commands that might help:</p>
      <ol>
        <li>justify-content</li>
        <li>align-items</li>
        <li>flex-direction</li>
        <li>order</li>
        <li>align-self</li>
        <li>flex-wrap</li>
        <li>flex-flow</li>
        <li>align-conten</li>
      </ol>
    </div>
  </div>
</div>

</template>

<script>
export default {
  name: 'Project',
  props: {
    msg: String
  }
}
</script>

<style scoped>
  .container {
      display: flex;
      flex-direction: row;
  }

  .task-container {
    width: 45%;
  }

  .project-container {
    display: flex;
    border: 2px solid gray;
    height: 650px;
    width: 45%;
    /* TODO add style here */
  }


  /* box descriptors */
  .box {
    background: #42b983;
    border: 1px solid;
    margin: 5px;
    width: 100px;
    height: 100px;
  }

  .red {
    background: red;
  }

  .yellow {
    background: yellow;
  }

  .blue {
    background: blue;
  }
</style>
