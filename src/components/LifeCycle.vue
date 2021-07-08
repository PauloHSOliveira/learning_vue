<template>
    <div>
        <h1>Meu nome é: {{nome}}</h1>
    </div>
</template>

<script>
    export default {
        name:'LifeCycle',
        data() {
            return {
                nome: 'Teste'
            }
        },
        created() {
            this.nome = 'Paulo'
        },
        mounted() {
            setTimeout(() => {
                this.nome = 'Paulinho'
            }, 5000);
        }
    }
</script>