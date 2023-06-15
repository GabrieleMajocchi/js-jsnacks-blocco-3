<script>
export default {
    data(){
        return{
            links: [
                {ref: '#', link: 'Link 1'},
                {ref: '#', link: 'Link 2'},
                {ref: '#', link: 'Link 3'},
                {ref: '#', link: 'Link 4'},
            ],
        }
    },

    methods: {
        
    },
}
</script>

<template>
    <div v-for="link in links">
        <a :href="link.ref">{{link.link}}</a> <br>
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