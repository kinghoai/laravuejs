<template>
    <div class="my-component">
        <div>{{ message }}</div>
        <div><button @click="sayHello">Click me</button></div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'This is my first component using binding data'
            }
        },
        methods: {
            sayHello() {
                alert('Hello World')
            }
        }
    }
</script>

<style lang="scss" scoped>
    .my-component {
        color: red;
    }
</style>