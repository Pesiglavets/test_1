<template>
    <div> MAIN 
        <slot name="mainContent">

        </slot> 
    </div>
</template>

<script>

export default {
    name: "AppMain",
}
</script>

<style lang="scss" scoped>
    @import "../components/styles/appMain/app-main";
</style>