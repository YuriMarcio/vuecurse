<template>
    <h1>Olá vue! meu nome é {{ nome }} e minha profissão é : {{ profissão }}</h1>
</template>

<script>
    export default{
        name:'primeiroComponente',
        data(){
            return {
                nome:"yuru",
                profissão: "programador",

            }
        }
    }
</script>