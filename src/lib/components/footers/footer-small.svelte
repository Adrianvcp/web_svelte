<script>
  // make dynamic date to be added to footer
  let date = new Date().getFullYear();

  export let absolute = false;
</script>

<footer
  class="pb-6 {absolute
    ? 'absolute w-full bottom-0 bg-blueGray-800'
    : 'relative'}"
>
  <div class="container mx-auto px-4">
    <hr class="mb-6 border-b-1 border-blueGray-600" />
    <div class="flex flex-wrap items-center justify-center">
      <div
        class="text-sm text-blueGray-500 font-semibold py-1 text-center md:text-left"
      >
        Copyright © {date} 
        <span
          class="text-white text-sm font-semibold py-1"
        >
        &nbsp; Asistente virtual
        </span>
      </div>
    </div>
  </div>
</footer>
