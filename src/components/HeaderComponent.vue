<template>
    <header>
        {{ title }}
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent',
        data(){
            return{
                title:'cioao'
            }
        }
    }
</script>

<style lang="scss" scoped>
header{
    color:red
}
</style>