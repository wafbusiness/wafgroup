<script>
  export let overflowHidden = true;
</script>

<div
  class="max-w-[76rem] mx-auto px-4 lg:px-2 h-full"
  class:overflow-hidden={overflowHidden}
>
  <slot />
</div>
