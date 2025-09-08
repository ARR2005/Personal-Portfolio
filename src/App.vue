<script setup lang="ts">
  import Navigation from './components/Navigation.vue'
</script>

<template>
<div className="min-h-screen bg-gray-800">
  <Navigation />
  <section className="pt-24 pb-16 px-6">
    <div className="max-w-6xl mx-auto">
      <div className="relative">
        <div className="absolute inset-0 flex items-center justify-center opacity-5">
          <div className="text-[30rem] bg-gradient-to-r from-cyan-400 via-teal-500 to-fuchsia-600
           bg-clip-text text-transparent ">
            ARVI 
          </div>
        </div>

        <div className="relative z-10 text-center py-20">
          <h1 className="text-6xl md:text-8xl font-black mb-6 bg-gradient-to-r from-cyan-400 via-teal-500 to-fuchsia-600
           bg-clip-text text-transparent animate-in fade-in slide-in-from-bottom-8 duration-1000">
            Hello, I'm Aldwin Rich
          </h1>
        <p className="text-2xl md:text-3xl text-gray-200 mb-8 animate-in fade-in slide-in-from-bottom-8 duration-1000 delay-300">
            Full Stack Developer
        </p>
          <div className="flex flex-col sm:flex-row gap-4 justify-center animate-in fade-in slide-in-from-bottom-8 duration-1000 delay-500">
            <Link to="/use-case">
              <Button size="lg" className="text-lg px-8 py-4">
                View My Work
              </Button>
            </Link>
            <Link to="/contact">
              <Button variant="outline" size="lg" className="text-lg px-8 py-4">
                Get In Touch
              </Button>
            </Link>
          </div>
        </div>
      </div>
    </div>
  </section>

</div>         
</template>

<style scoped>

</style>
