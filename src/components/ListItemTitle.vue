<template>
    <p style="color: green">{{ title }}</p>
</template>

<script>
export default {
    name: "ListItemTitle",
    props: {
        title: {
            type: String,
            required: true,
        }
    }
}
</script>

<style>

</style>