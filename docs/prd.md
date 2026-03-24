# 🎮 Gamory — Product Requirements Document (PRD)

## 📌 1. Visão Geral
Gamory é uma aplicação web inspirada no Letterboxd, focada no registro, avaliação e organização de jogos digitais.
6O sistema permite que usuários cadastrem jogos, atribuam notas e escrevam comentários, criando um histórico pessoal de experiências.

---

## 🎯 2. Objetivo do Produto
Desenvolver uma aplicação web responsiva que permita:
- Cadastro de jogos
- Avaliação (nota)
- Comentários
- Visualização de lista de jogos

---

## 👤 3. Público-Alvo
- Estudantes
- Gamers casuais e hardcore
- Usuários que desejam organizar jogos jogados

---

## 🚀 4. Funcionalidades Principais

### 📥 Cadastro de Jogos
- Inserir título
- Selecionar gênero
- Selecionar plataforma
- Atribuir nota (1 a 5)
- Adicionar comentário

---

### 📋 Listagem de Jogos
- Exibição em cards ou tabela
- Mostrar título, gênero e nota
- Atualização dinâmica via API

---

### ✏️ Edição e Exclusão (Opcional)
- Editar informações de jogos
- Excluir jogos cadastrados

---

### 💾 Persistência de Dados
- Armazenamento local (LocalStorage)
- Integração com API (JSON Server)

---

### 🌐 Integração com API
- Envio e leitura de dados via requisições assíncronas
- Consumo de API pública (ViaCEP)

---

## 📱 5. Requisitos de Interface

- Layout responsivo (mobile e desktop)
- Uso de Bootstrap
- Interface moderna e simples
- Design consistente (cores e tipografia)

---

## ✅ 6. Requisitos Funcionais

- RF01: O sistema deve permitir cadastro de jogos
- RF02: O sistema deve validar os campos obrigatórios
- RF03: O sistema deve listar jogos cadastrados
- RF04: O sistema deve persistir dados localmente
- RF05: O sistema deve consumir API fake (JSON Server)
- RF06: O sistema deve consumir API pública

---

## ⚙️ 7. Requisitos Não Funcionais

- RNF01: Interface responsiva
- RNF02: Tempo de resposta rápido
- RNF03: Código organizado e modular
- RNF04: Compatível com navegadores modernos

---

## 📊 8. Métricas de Sucesso

- Cadastro funcionando corretamente
- Listagem exibida corretamente
- Integração com API funcionando
- Layout responsivo validado

---

## 🧪 9. Critérios de Aceitação

- O usuário consegue cadastrar um jogo com sucesso
- Os dados aparecem na listagem
- Validações impedem envio incorreto
- API responde corretamente
- Interface se adapta a diferentes telas

---

## 🗓️ 10. Escopo do Projeto

- 3 páginas HTML
- Formulário com validação
- API fake
- LocalStorage
- Responsividade
