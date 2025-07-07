<script>
    export let category = "Eindrücke";
    export let description = "";
    export let orientation = "right";

    let orientationClass = orientation === "left" ? "text-left" : "text-right"; 
</script>

<div class="{orientationClass} grid grid-flow-col">
    {#if orientation==="left"}
    <h1 class="text-[#03A696] text-5xl font-bold mr-10 w-[300px]">
        {category}
    </h1>
    {/if}
        <div class="w-xl text-left max-w">
            <slot></slot>
        </div>
    {#if orientation==="right"}
        <h1 class="text-[#03A696] text-5xl font-bold w-[300px]">
            {category}
        </h1>
    {/if}
    
</div>