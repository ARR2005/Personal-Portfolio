<script setup lang="ts">
    import {Button} from "@/components/ui/button"
</script>

<template> 
  <div class="fixed top-0 left-0 right-0 z-50 bg-slate-200 backdrop-blur-md border-b-2 border-grey-200">
    <div class="max-w-6xl mx-auto px-6 py-4">
        <div class="flex items-center justify-between">
            <a href="#">
                Portfolio
            </a>
        </div>
        <nav class="hidden md:flex space-x-2">
            <Button variant="ghost" size="lg" id="button1"> {{ nav.Home }}</Button>
            <Button variant="ghost" size="lg" id="button2"> {{ nav.Skill }}</Button>
            <Button variant="ghost" size="lg" id="button3"> {{ nav.Case }}</Button>
            <Button variant="ghost" size="lg" id="button4"> {{ nav.Contact }}</Button>
        </nav>
    </div>
  </div>
</template>

<script lang="ts">
    const nav = {
        Home:"Home",
        Skill:"Skills",
        Case:"Case",
        Contact:"Contacts"
        }
</script>


<style scoped>

</style>