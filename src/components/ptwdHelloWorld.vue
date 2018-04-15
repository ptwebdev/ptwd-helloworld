<template>
    <div>
        <span v-model="output"></span>
    </div>
</template>

<script>
    export default {
        name: "ptwdHelloWorld",
        props: ['text'],
        data: function () {
            return {
                output: 'Hello World'
            }
        },
        mounted: function () {
            if (this.text) {
                this.output = this.text
            } else {
                this.output = this.output
            }
        }
    }
</script>

<style scoped>

</style>