<!--
 * @作者: kerwin
 * @公众号: 大前端私房菜
-->
<template>
    <div>
        login

        <button @click="handleLogin">login</button>
    </div>
</template>

<script setup>

const handleLogin = ()=>{
    localStorage.setItem("token","kerwin")
}
</script>

