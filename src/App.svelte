<script lang="ts">
  import DiGithubBadge from 'svelte-icons/di/DiGithubBadge.svelte'

  const title = "Vite + Svelte + TypeScript + TailwindCSS";
</script>

<main class="w-screen h-screen flex flex-col gap-4 justify-center items-center p-5">
  <h1 class="text-3xl font-bold text-center">{title}</h1>
  <h2 class="text-2xl text-zinc-400 flex flex-col gap-2 md:flex-row">A starter template by 
    <a target="_blank" rel="noreferrer" class="italic text-teal-500 flex justify-center items-center hover:scale-95 hover:text-teal-700 transition-all" href="https://github.com/wwessel01">
      wwessel01
      <div class="w-6 h-6 mt-1">
        <DiGithubBadge />
      </div>
    </a>
  </h2>
</main>