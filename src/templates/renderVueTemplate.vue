<template>
  <div>
      <section>
          <label>Write some text:</label><br>
          <input type="text" v-model="text">
      </section>
      <section style="margin-top: 20px;">
          <p class="output">
              {{ text }}
          </p>
      </section>
  </div>
</template>

<script>
export default {

}
</script>

<style id="">
.output {
    font-size: 3rem;
    color:deeppink;
}
</style>