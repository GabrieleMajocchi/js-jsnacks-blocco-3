<script>
export default {
    
}
</script>

<template>
    <div>
        <a href="#">Link 1</a>
        <a href="#">Link 1</a>
        <a href="#">Link 1</a>
        <a href="#">Link 1</a>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

div{
    a{
        text-decoration: none;
        margin: 1rem 0;
        color: $primaryColor;
    }
}

</style>