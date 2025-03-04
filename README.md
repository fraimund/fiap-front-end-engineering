# Meu Portfólio Pessoal

Este é um portfólio pessoal desenvolvido utilizando as tecnologias **Node.js**, **Vue.js**, e **TailwindCSS**. O site tem como objetivo exibir informações sobre mim e fornecer links para meus perfis nas redes sociais.

## Tecnologias Utilizadas

- **Node.js**: Backend do projeto
- **Vue.js**: Framework JavaScript para construir a interface do usuário
- **TailwindCSS**: Framework CSS utilitário para estilização

## Funcionalidades

- Exibição de foto e informações pessoais.
- Links para redes sociais, como LinkedIn, WhatsApp, Instagram e GitHub.
- Design responsivo, adaptando-se a diferentes tamanhos de tela.

## Rodando o Projeto Localmente

### Requisitos

- Node.js instalado (preferencialmente a versão LTS).

### Passos para rodar o projeto

1. Clone o repositório:
   bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   

2. Navegue até o diretório do projeto:
   bash
   cd nome-do-repositorio
   

3. Instale as dependências:
   bash
   npm install
   

4. Inicie o servidor de desenvolvimento:
   bash
   npm run dev
   

5. Abra o navegador e acesse a URL `http://localhost:3000` (ou a porta especificada no terminal).

## Como Fazer o Build do Projeto

Para criar uma versão otimizada para produção, utilize o comando abaixo:

bash
npm run build


Isso irá gerar os arquivos estáticos na pasta `dist/`, que podem ser enviados para um servidor de produção.

## Como Entregar o Projeto em Produção

1. **GitHub + Netlify**:
   - Crie um repositório no GitHub.
   - Faça o push do código para o repositório.
   - Conecte seu repositório do GitHub com o Netlify.
   - O Netlify cuidará do processo de build e deployment automaticamente.

2. **Configuração no Netlify**:
   - Na página do Netlify, clique em "New Site from Git".
   - Escolha o repositório GitHub que você criou.
   - O Netlify irá automaticamente detectar o framework (Vite, neste caso) e configurar as etapas de build.
   - Após o deploy, seu site estará online com um link fornecido pelo Netlify.

## Estrutura do Projeto


/src
  /components
    ButtonAction.vue          # Componente de Botão com Ação
    ProfileInfo.vue           # Componente de Informações do Perfil
  /assets
    foto.jpg                  # Foto do perfil
  main.js                     # Arquivo de entrada do Vue
/public
  index.html                  # Arquivo principal de HTML


## Considerações Finais

Este projeto tem como objetivo demonstrar minhas habilidades de front-end, usando as tecnologias mencionadas para construir uma interface simples, mas funcional. Ele está hospedado no Netlify e pode ser acessado diretamente [aqui](https://rm-357059-front-end-engineering.netlify.app/).

## Contribuindo

Sinta-se à vontade para fazer contribuições! Caso queira melhorar ou adicionar novas funcionalidades, basta criar um fork do projeto e enviar um pull request.

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.