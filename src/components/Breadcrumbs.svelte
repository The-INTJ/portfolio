<script>
  export let links;
</script>

<div class="text-md breadcrumbs text-secondary absolute left-4 top-20">
  <ul>
    {#each links as link}
      <li class="before:text-primary before:!opacity-100 decoration-wavy">
        <a href={link.href}>{link.name}</a>
      </li>
    {/each}
  </ul>
</div>
