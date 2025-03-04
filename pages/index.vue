<template>
    <ProfileInfo photo="/foto.jpg"
                 title="Fábio A. Raimundo" 
                 subtitle="fabio.ap.raimundo@gmail.com" 
                 headline="Tech Manager | Data Enginer | Product Lead" />

    <main class="max-w-xs mx-auto">
        <ButtonAction link="https://www.linkedin.com/in/fabio-a-raimundo-842a8b14/"
                      icon="👤"
                      title="Linkedin"
        />
        <ButtonAction link="https://wa.me/5512996474944"
                      icon="🗨"
                      title="WhatsApp"
        />
        <ButtonAction link="https://www.instagram.com/fabio.a.raimundo/"
                      icon="👨‍👩‍👧‍👦"
                      title="Instagram"
        />
        <ButtonAction link="https://github.com/fraimund"
                      icon="👨🏾‍💻"
                      title="github"
        />
    </main>

    <div id="app" class="relative min-h-screen">
        <header class="p-4">
        <button @click="openModal" class="mt-4 px-4 py-2 bg-blue-500 text-white rounded">Saiba Mais Sobre Mim</button>
        </header>
        <Modal :isOpen="isModalOpen" :description="description" @close="isModalOpen = false" />
    </div>

</template>

<script>
import Modal from './components/Modal.vue';

export default {
  components: {
    Modal
  },
  data() {
    return {
      isModalOpen: false,
      description: "Sou um engenheiro de dados que adora explorar o mundo do front-end. Tenho experiência em trabalhar com dados e estou sempre em busca de novas tecnologias e desafios para aprimorar minhas habilidades na criação de interfaces interessantes"
    };
  },
  methods: {
    openModal() {
      this.isModalOpen = true;
    }
  }
};
</script>