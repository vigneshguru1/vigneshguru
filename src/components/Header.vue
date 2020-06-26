<template>
  <div tabs>
    <b-nav>
      <b-nav-item disabled>
        <b>Quiz App</b>
      </b-nav-item>
      <b-nav-item disabled>Questions:{{numCorrect}}/{{numTotal}}</b-nav-item>
    </b-nav>
  </div>
</template>
<script>
export default {
  props: ["numCorrect", "numTotal"]
};
</script>