<template>
<form class="form" @submit.prevent="handleSubmit">
    <label>
        <input type="text">
        <label>

</form>
</template>

<script>
export default {
    name: "custom-input",
    props: {
        
        }
    ,methods: {
        handleSubmit() {
            console.log('Submitted')
            }
    }
    
</script>
<style scoped lang="scss">
.form {
    margin: auto;
    height: 100px;
    width: 100px;
    box-shadow: 15px 15px red;
}
</style>