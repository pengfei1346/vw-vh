<template>
    <div id="app">
        <h3>Vuex购物车demo</h3>
        <!-- 商品的列表 -->
        <product></product>
        <!-- 购物车的列表 -->
        <cart></cart>
        <!-- 小记 -->
        <info></info>
    </div>
</template>

<script>
    import product from '../components/cart/product';
    import cart from '../components/cart/cart';
    import info from '../components/cart/info';

    export default {
        name: 'app',
        components: {
            product,
            cart,
            info
        },
        mounted() {
            setTimeout(() => {
                alert(`6666+${8888}`)
            })
        }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
</style>