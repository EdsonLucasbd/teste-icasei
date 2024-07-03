# Projeto de Microfrontends

Este projeto demonstra a implementação de microfrontends utilizando componentes web personalizados, com um backend em Node.js para gerenciar os dados. O objetivo é criar uma aplicação modular que possa ser facilmente mantida e escalada.

## Estrutura do Projeto

- mf_drawer/: Componente do menu lateral

- mf_videos/: Componente da lista de vídeos e favoritos

- bff/: Servidor Node.js para servir e gerenciar os dados de cada microfrontend

## Funcionalidades

- Menu Lateral: Exibe opções de navegação (Vídeos e Favoritos)
- Lista de Vídeos: Exibe vídeos correspondentes com o termo buscado

- Favoritos: Adicionar e remover vídeos dos favoritos, com atualização em tempo real do badge no menu lateral

## Tecnologias Utilizadas

- Node.js: Backend para gerenciar os favoritos
- Express: Framework para servidor Node.js
- Web Components: Para criar componentes reutilizáveis
- LocalStorage: Para armazenar favoritos no navegador
- SCSS: Para estilização dos componentes
- Typescript: Para tipagem estática

## Instruções de Instalação

#### 1. Clone o repositório:

```bash
git clone https://github.com/EdsonLucasbd/teste-icasei

cd teste-icasei
```

#### 2. Instale as dependências:

```bash
cd bff

npm install
```

#### 3. Inicie o servidor:

```bash
npm run start
```

#### 4. A aplicação estará rodando na porta 3000:

http://localhost:3000/mf_drawer/dist/

## Contribuições

Para contribuir com este projeto, faça um fork do repositório, crie uma branch para sua feature ou correção de bug e abra um pull request.

## Licença

Este projeto está licenciado sob a licença MIT.
