<template>
    <div>
        <h1>meu nome é :{{ nome }} </h1>
    </div>
</template>

<script>
    export default{
        name:"lifeCicle",
        data(){
            return{
                nome:"ainda não sei "
            }
        },
        created(){
            setTimeout(() => {
                this.nome = 'yuri'
            },1000)
        },
        mounted(){
            setTimeout(() => {
                this.nome = 'chuchu'
            },2000)
        }
    }
</script>