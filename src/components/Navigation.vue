<script setup lang="ts">
    import {Button} from "@/components/ui/button"
</script>

<template> 
<header class="fixed top-0 left-0 right-0 z-5 bg-transparent backdrop-blur-md border-b-1 border-grey-200 flex flex-row">
    <div class="h-15 min-w-full flex flex-row items-baseline-last justify-around w-80 ">
    <div class="font-extrabold w-30 size-10 text-center   ">
            <a href="#">
                Portfolio
            </a>
        </div>
        <div>
            <nav class="hidden md:flex space-x-2">
                <Button variant="outline" size="lg" id="button1"> {{ nav.Home }}</Button>
                <Button variant="outline" size="lg" id="button2"> {{ nav.Skill }}</Button>
                <Button variant="outline" size="lg" id="button3"> {{ nav.Case }}</Button>
                <Button variant="outline" size="lg" id="button4"> {{ nav.Contact }}</Button>
            </nav>
        </div>
    </div>

</header>
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