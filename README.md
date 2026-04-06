# 📱 Habit-Flow Client

## 📌 Visão Geral

O **Habit-Flow-client** é a aplicação front-end responsável pela interação do usuário com o sistema de gerenciamento de hábitos. Ele permite criar, visualizar, editar e acompanhar hábitos de forma simples e intuitiva em múltiplas plataformas (iPhone, Android, Web e Smartwatch).

---

## 🧠 Arquitetura (MVP)

![Arquitetura do Sistema](https://private-user-images.githubusercontent.com/179618517/573706621-8dbc8e2f-c165-4434-92b4-6e68e96a92e0.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzU0NDQ4MzIsIm5iZiI6MTc3NTQ0NDUzMiwicGF0aCI6Ii8xNzk2MTg1MTcvNTczNzA2NjIxLThkYmM4ZTJmLWMxNjUtNDQzNC05MmI0LTZlNjhlOTZhOTJlMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDA2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQwNlQwMzAyMTJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02NTY0NWU0MjBmY2FjYjdlZDYxN2I5ZjFmZGFkMTIyMzIxNzVkMThhNjJlM2NiYWMyMjdiOGRmNWQ4NTBiZDIwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.J8slsnA7ee9c9VbifW60hpFmhZCsCwOV9zC5nfyeQxY)

### 🔎 Explicação da imagem:

A imagem mostra o fluxo básico do sistema (MVP):

* **Front-End / App**: Onde o usuário interage.

  * Cria hábitos com informações como:

    * ID
    * Prioridade
    * Horário
    * Título
    * Público ou privado
    * Obrigatório ou opcional
    * Tipo de hábito

* **Back-End**:

  * Valida os dados
  * Salva hábitos
  * Atualiza hábitos
  * Exclui hábitos
  * Consulta hábitos existentes

* **Banco de Dados**:

  * Armazena todas as informações
  * Faz operações de salvar, atualizar e excluir

👉 Resumindo: o Client envia dados → Backend processa → Banco salva.

---

## 🎯 Objetivo

Fornecer uma interface amigável para que o usuário consiga:

* Criar novos hábitos
* Acompanhar progresso
* Editar informações
* Excluir hábitos
* Visualizar estatísticas

---

## 📲 Interface do Usuário

![Interfaces do App](https://github.com/user-attachments/assets/c5f5909c-2a1e-45ae-b8cf-6a54b41f8576)

### 🔎 Explicação da imagem:

A imagem mostra como o app funciona em diferentes plataformas:

### 📱 iPhone / Android

* Lista de hábitos
* Botão **+** para adicionar
* Marcar hábito como concluído (✔️)
* Exibir sequência de dias (🔥 streak)
* Navegação inferior:

  * Hábitos
  * Estatísticas
  * Perfil

### 💻 Web / PC

* Menu lateral (Hábitos, Stats, Profile)
* Área maior para visualizar detalhes
* Melhor para gerenciamento completo

### ⌚ Smartwatch

* Interface simples
* Foco em ações rápidas
* Marcar hábitos com um toque

---

## 📲 Funcionalidades Principais

### 1. Criar Hábito

Permite adicionar um novo hábito com informações básicas.

### 2. Listar Hábitos

Exibe todos os hábitos cadastrados com status e progresso.

### 3. Marcar como Concluído

Usuário marca tarefas realizadas no dia.

### 4. Editar Hábito

Atualiza dados do hábito.

### 5. Excluir Hábito

Remove o hábito do sistema.

### 6. Estatísticas

Mostra evolução e desempenho do usuário.

---

## 🔗 Comunicação com Backend

O client se comunica com o backend através de requisições HTTP:

* GET → Buscar hábitos
* POST → Criar hábito
* PUT/PATCH → Atualizar hábito
* DELETE → Excluir hábito

---

## 🗂️ Estrutura Sugerida do Projeto

```
Habit-Flow-client/
│
├── src/
│   ├── components/
│   ├── screens/
│   ├── services/ (API)
│   ├── hooks/
│   ├── styles/
│   └── utils/
│
├── assets/
├── package.json
└── README.md
```

---

## 🚀 Tecnologias Sugeridas

* React / React Native
* TypeScript
* Axios (requisições HTTP)
* Expo (para mobile)

---

## 🔐 Considerações de Segurança

* Autenticação de usuário (JWT)
* Proteção de rotas
* Validação de dados

---

## 📈 Possíveis Melhorias Futuras

* Notificações push
* Gamificação (pontos e conquistas)
* Sincronização offline
* Integração avançada com smartwatch

---

## ✅ Conclusão

O Habit-Flow-client é a parte visual essencial do sistema, responsável por entregar uma experiência intuitiva e eficiente para o usuário acompanhar e melhorar seus hábitos diariamente.
