<script>
  export let title;
</script>

<div class="TitleDescription">
  <h3>{title}</h3>
  <slot name="p-tag" />
</div>

<style>
  .TitleDescription {
    @apply mx-auto px-6 lg:px-[2.5%];
  }
</style>
