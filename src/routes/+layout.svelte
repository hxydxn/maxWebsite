<script>
    import "../app.css";
    import Footer from "./footer.svelte";
  </script>
  
  <body>
    <div class="fixed h-screen w-full bg-gradient-to-br from-zinc-50 to-zinc-100" />
    <main class="flex min-h-screen w-full flex-col items-center justify-center py-32">
        <slot />
    </main>
    <Footer />
  </body>