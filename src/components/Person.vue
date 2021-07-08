<template>
    <div>
        <h2>Me chamo {{name}}</h2>
        <Info />
        <Form />
    </div>
</template>

<script>

import Info from './Info.vue'
import Form from './Form.vue'

export default {
    name:'Person',
    components: {
        Info,
        Form
    },
    data() {
        return {
            name:'Paulo'
        }
    }
}
</script>