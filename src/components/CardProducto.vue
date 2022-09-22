<template>
    <GridProducto>
        <img v-bind:src="url" :alt="nombre">
        <h2>{{ nombre }}</h2>
        <h6><small>{{ desc }}</small></h6>
        <h2>{{ precio }}</h2>
        <a :href="url" target="_blank">Visitar</a>
    </GridProducto>
</template>

<script>
    import GridProducto from './GridProducto.vue';

    export default{

        props: {
        url: { String, },
        nombre: { String, },
        desc: { String, },
        precio: { String, },
        },

        components: { GridProducto }
    };
</script>

<style scoped>
    
    img{
        width: 8rem;
        height:  8rem;
        padding: 0.5rem;
        background: snow;
    }

    a{
        text-decoration: none;
        color: snow;
        background: #301675;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }

    h3{
     word-wrap: break-word;
     -webkit-hyphens: auto;
     -moz-hyphens: auto;
     -ms-hyphens: auto;
     -o-hyphens: auto;
     hyphens: auto;
    }
</style>