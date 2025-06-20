# Aplicativo de Mensagens Híbrido - Prova 2 (Trabalho Final)

## Sobre o Projeto

Este projeto é o resultado da **Prova 2 - Trabalho Final** da disciplina de Aplicativos Híbridos. O objetivo foi evoluir um aplicativo de mensagens já existente, partindo do código-base disponível em [https://github.com/loyoladesa/AplicativosHibridos2025-1/tree/whatsapp-firebase](https://github.com/loyoladesa/AplicativosHibridos2025-1/tree/whatsapp-firebase), implementando novas funcionalidades obrigatórias e diferenciais criativos, utilizando **React Native** no frontend e **Firebase** (Realtime Database, Authentication e Storage) no backend.

---

## Funcionalidades Obrigatórias Implementadas

- **Conversas Particulares (Destinatário):**
  - Mensagens são enviadas especificamente para um usuário (destinatário).
  - O sistema identifica e exibe conversas separadas entre diferentes pares de usuários.
  - É possível listar contatos/usuários e iniciar uma conversa particular.

- **Destaque para Mensagens do Próprio Usuário:**
  - Mensagens enviadas pelo usuário logado têm destaque visual diferente (alinhamento à direita, cor de fundo diferente).

- **Envio de Arquivos:**
  - Permite envio de imagens e documentos PDF.
  - Exibe miniatura ou link para o arquivo na conversa.

- **Confirmação de Visualização de Mensagem:**
  - Sistema de indicação de visualização (✔ e ✔✔ azul) atualizado em tempo real.

- **Exibição da Hora de Envio:**
  - Cada mensagem mostra o horário em que foi enviada.

- **Criação de Logotipo:**
  - Logotipo original desenvolvido e integrado ao aplicativo.

- **Edição de Mensagem Enviada:**
  - Permite editar o conteúdo de uma mensagem já enviada.

---

## Diferenciais Criativos

- **Envio de emojis:**  
  O usuário pode abrir um seletor de emojis e inserir emojis em qualquer mensagem, tanto em conversas particulares quanto em grupos, tornando a comunicação mais divertida e expressiva.

- **Apagar mensagem para ambos:**  
  O usuário pode apagar uma mensagem para todos os participantes da conversa, não apenas para si mesmo, semelhante ao recurso de "apagar para todos" dos principais aplicativos de mensagens.

---

## Tecnologias e Integrações

- **Login com e-mail e senha:**  
  Utilizamos o Firebase Authentication para autenticação por e-mail e senha, garantindo mais segurança e praticidade para os usuários.

- **Armazenamento de arquivos:**  
  Utilizamos o Firebase Storage para armazenar arquivos enviados nas conversas, como imagens e PDFs.

- **Sincronização em tempo real:**  
  Todas as mensagens, grupos e contatos são gerenciados pelo Firebase Realtime Database, garantindo atualização instantânea das conversas para todos os usuários conectados.

---

## Como rodar o projeto

1. Clone o repositório ou extraia o arquivo compactado.
2. Instale as dependências com `npm install` ou `yarn`.
3. Configure o arquivo `config/Firebase.js` com suas credenciais do Firebase.
4. Execute com `npx expo start` ou `expo start`.

---

## Créditos

Desenvolvido por:
- Denis Gomes Bomfim - 202211029
- Marcos Luiz de Souza Reis - 202211072

---

Este projeto foi desenvolvido como parte da disciplina de Aplicativos Híbridos - Prova 2 (Trabalho Final).