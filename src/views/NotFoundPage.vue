<template>
    <div>Page is not found</div>
</template>

<script>
    export default {
        name: "NotFoundPage",
        created() {
            console.log(document.location.href)
        }
    }
</script>

<style scoped>

</style>