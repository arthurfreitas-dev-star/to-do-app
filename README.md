# 📝 To-Do Pro

Uma aplicação moderna de lista de tarefas (To-Do List) desenvolvida com **HTML, CSS e JavaScript puro**, focada em boas práticas de desenvolvimento front-end, organização de código e experiência do usuário.

---

## 🚀 Funcionalidades

### ✅ Gerenciamento de tarefas

* Adicionar novas tarefas
* Editar tarefas existentes
* Remover tarefas
* Marcar como concluída

### 🎯 Prioridades

* Definição de prioridade:

  * 🔴 Alta
  * 🟡 Média
  * 🟢 Baixa
* Estilização visual dinâmica baseada na prioridade

### 🔍 Filtros inteligentes

* Visualizar:

  * Todas as tarefas
  * Apenas pendentes
  * Apenas concluídas

### 📊 Feedback ao usuário

* Contador de tarefas pendentes em tempo real

### 💾 Persistência de dados

* Armazenamento local com `localStorage`
* Os dados permanecem mesmo após recarregar a página

### ⚡ Melhor experiência (UX)

* Adicionar tarefas pressionando **Enter**
* Interface responsiva e intuitiva
* Atualização dinâmica da interface

### 🌙 Tema Dark Mode

* Alternância entre modo claro e escuro

### ♿ Acessibilidade básica

* Uso de atributos `aria-label`
* Melhor navegação e usabilidade

---

## 🧱 Estrutura do Projeto

```
to-do-pro/
│
├── index.html   # Estrutura principal + CSS + JS
└── README.md    # Documentação do projeto
```

---

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3 (com variáveis CSS)
* JavaScript (Vanilla JS)
* Web Storage API (`localStorage`)

---

## 🧠 Arquitetura e Boas Práticas

### 📦 Estrutura de dados

Cada tarefa é representada como um objeto:

```
{
  id: Number,
  text: String,
  priority: "alta" | "media" | "baixa",
  done: Boolean
}
```

### 🔁 Renderização

* A interface é atualizada dinamicamente via função `render()`
* Separação entre dados (estado) e UI

### 💡 Organização do código

Funções principais:

* `addTask()` → adiciona tarefa
* `deleteTask()` → remove tarefa
* `toggleDone()` → marca como concluída
* `editTask()` → edita tarefa
* `render()` → atualiza interface
* `save()` → salva no localStorage

---

## 📦 Como executar o projeto

1. Clone ou baixe este repositório:

```
git clone https://github.com/seu-usuario/to-do-pro.git
```

2. Abra o arquivo:

```
index.html
```

3. Execute diretamente no navegador

---

## 📈 Melhorias implementadas

✔ Persistência com `localStorage`
✔ Filtros dinâmicos
✔ Ordenação por prioridade
✔ Estrutura de dados escalável
✔ UX aprimorada (Enter, feedback visual)
✔ Dark Mode com CSS variables
✔ Código organizado e reutilizável

---

## 🔮 Possíveis melhorias futuras

* Drag and Drop para reordenar tarefas
* Integração com backend (Node.js / Firebase)
* Autenticação de usuário
* Datas e prazos (deadline)
* Notificações
* Transformação em SPA (React ou Vue)
* Testes automatizados

---

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de:

* Praticar JavaScript puro (sem frameworks)
* Aplicar conceitos de manipulação de DOM
* Trabalhar com armazenamento local
* Simular uma aplicação real de produtividade
* Criar um projeto de portfólio

---

## 📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar, modificar e distribuir.

---

## 👨‍💻 Autor

Desenvolvido por você 🚀
(Sugestão: adicione seu nome e GitHub aqui)

---
