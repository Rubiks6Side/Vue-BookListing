<template>
    <h1>{{ title }}</h1>
    <ul>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</template>

<script>
    export default{
        name: 'BookList',
        data: {
            title: 'All Books'
        },
    }
</script>

<style scoped>
    h1, h2 {
        font-weight: normal;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: block;
        margin: 0 10px;
    }
</style>
