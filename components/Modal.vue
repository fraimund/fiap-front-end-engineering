<template>
    <div class="fixed inset-0 flex items-center justify-center bg-gray-900 bg-opacity-50" v-if="isOpen">
    <div class="bg-white p-6 rounded-lg shadow-lg max-w-lg w-full">
        <h2 class="text-xl font-semibold mb-4">Sobre Mim</h2>
        <p>{{ description }}</p>
        <button @click="close" class="mt-4 px-4 py-2 bg-blue-500 text-white rounded">Fechar</button>
    </div>
    </div>
</template>

<script>
export default {
    props: {
    isOpen: {
        type: Boolean,
        required: true
    },
    description: {
        type: String,
        default: "Adicione sua descrição aqui."
    }
    },
    methods: {
    close() {
        this.$emit('close');
    }
    }
};
</script>

<style scoped>
/* Adicione estilos personalizados para o modal, se necessário */
</style>