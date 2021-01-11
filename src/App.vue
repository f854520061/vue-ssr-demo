<template>
  <div id="app">
    <ul>
        <li>
            <router-link to="/">Home</router-link>
        </li>
        <li>
            <router-link to="/about">About</router-link>
        </li>
        <li>
            <router-link to="/posts">Posts</router-link>
        </li>
    </ul>

    <!-- 路由出口 -->
    <router-view/>
    <!-- <h1>{{ message }}</h1>
    <h2>客户端动态交互</h2>
    <div>
        <input v-model="message">
    </div>
    <div>
        <button @click="onClick">点击测试</button>
    </div> -->
</div>
</template>

<script>
export default {
    name: 'App',
    data () {
        return {
             message: '拉勾教育'
        }
    },
    methods: {
        onClick () {
            console.log('Hello World!')
        }
    }
}
</script>

<style>

</style>