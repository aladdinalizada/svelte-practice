<script>
  export let name;
</script>

<div>
  <h1>
    Hello {name}!
  </h1>
</div>

<style lang="scss">
  @import "styles/variables.scss";

  div {
    h1 {
      color: red;
      //   font-weight: @font-weight;
      font-family: $font-style;
    }
  }
</style>
