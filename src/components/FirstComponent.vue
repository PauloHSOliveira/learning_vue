<template>
   <div>
        <h1>Olá Vue!</h1>
        <p>Desenvolvido por {{name}}</p>
        <p>Ocupação: {{ocupation}}</p>
   </div>   
</template>

<script>
    export default {
        name:'FirstComponent',
        data() {
            return {
                name:"Paulo",
                ocupation:"Fullstack developer"
            }
        }
    }
</script>