<template>
  <main class="min-h-screen w-full">
    <div class="flex flex-col md:flex-row h-full w-full">
      <AdminSidebar/>
      <section class="ml-60 w-full bg-zinc-50 min-h-screen">
        <slot />
      </section>
    </div>
  </main>
</template>