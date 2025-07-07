<script>
    import Header from "./header.svelte";
    import Allgemein from "./allgemein.svelte";
    import Rundgang from "./rundgang.svelte";
    import Intro from "./intro.svelte";
</script>

<Header></Header>
<div class="w-full grid justify-items-center">
    <div class="max-w-[1220px] divide-y-2 divide-[#cccccc] space-y-16">
        <Intro></Intro>
        <Allgemein></Allgemein>
        <Rundgang></Rundgang>
    </div>
</div>