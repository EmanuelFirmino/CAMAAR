<template>

    <button class='btn-logged' type='button'> {{ btn_name }} </button>

</template>


<script>

    export default {
        name: 'ButtonLoggedPage',
        data() {
            return {
                btn_name: 'BTN_VALUE',
            }
        },
    }

</script>

<style scoped >

    .btn-logged {
        position: relative;
        width: 289px;
        height: 50px;
        border: none;
        margin: 10px;
        font-family: Inter;
        font-size: 24px;
        background: #ffffff;
    }

    .btn-logged:focus, .btn-logged:hover {
        background: linear-gradient(0deg, #7AC7FF, #7AC7FF), linear-gradient(0deg, #FFFFFF, #FFFFFF), #FFFFFF;
    }

</style>