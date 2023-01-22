<template lang="pug">
#app
  section.sheet.padding-10mm
    Brand
    // Your custom components go here
    hr
    h1 Vue App template
    .head1 Vue Templates
    ul
      li Using pug
  section.sheet.padding-10mm
    p Some other stuff...
    p More stuff
</template>

<script lang="ts">
import Brand from "@/components/Head";

export default {
  components: { Brand },
};
</script>

<style lang="scss" scoped>
@page {
  size: A5;
}

.head1 {
  text-align: center;
}
</style>