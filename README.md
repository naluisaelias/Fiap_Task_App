# ✅ Task APP

Gerenciador de tarefas em formato de checklist para organização de atividades diárias. O aplicativo permite criar, visualizar e gerenciar tarefas, agrupando-as de maneira prática e funcional, com uma interface intuitiva.

Este projeto foi desenvolvido como parte do **Checkpoint 06** da disciplina **'Desenvolvimento Cross Platform'** ministrada pelo professor **Diego Camilo Martins Vieira**.

## 📲 Funcionalidades
* **Gerenciamento de tarefas:** Criação, edição e exclusão de tarefas.
* **Agrupamento por categorias:** Organização das tarefas em grupos.
* **Visualização diária:** Exibição de tarefas específicas para cada dia, com seleção de datas via calendário.
* **Modo claro e escuro:** Alternância automática entre temas para uma experiência personalizada.

## ⚙️ Tecnologias Utilizadas
* **Flutter:** Framework para desenvolvimento do aplicativo multiplataforma.
* **Dart:** Linguagem de programação utilizada no Flutter.
* **Provider:** Gerenciamento de estado.
* **Supabase:** Backend para autenticação e persistência de dados.
* **Material Design 3:** Design system para uma interface moderna e consistente.

## 👨🏻‍🏫 Orientações do Checkpoint

Implementar funcionalidades adicionais em um aplicativo de gerenciamento de tarefas usando o Provider para o gerenciamento de estado. **O uso do Provider é obrigatório para o gerenciamento de estado** .

### 📝 Tarefas

#### Tarefa 01: Alternar Tema do Aplicativo

**Objetivo:** Implementar uma funcionalidade que permita alternar o tema do app entre claro e escuro ao clicar no ícone de alternar tema. 

**Especificações:**
* Utilize o Provider para gerenciar o estado do tema.
* Defina os temas claro e escuro dentro do Material App.
* Ao clicar no icone, o tema deve alternar entre claro e escuro em todo o app. 

#### Tarefa 02: Cadastrar Grupos de Tarefas 

**Objetivo:** Adicionar a funcionalidade de cadastro de grupos de tarefas. 

**Especificações:**
* Utilizar a tela de cadastro de grupos de tarefas, onde o usuário poderá inserir o nome, cor e ícone do grupo.
* Cada grupo deve ser salvo em um Provider de grupos de tarefas e no banco de dados Supabase.
* Ao salvar, o grupo de tarefas deve aparecer na lista de grupos do app.

#### Tarefa 03: Remover Grupo de Tarefas 

**Objetivo:** Permitir a remoção de grupos de tarefas. 

 **Especificações:**
* Adicione uma ação de exclusão para cada grupo na lista.
*  Ao realizar exclusão, o grupo deve ser removido da lista.
* Confirme a exclusão com um ```AlertDialog``` antes de remover o grupo permanentemente.

 #### Tarefa 4: Marcar e Desmarcar Tarefa como concluída 

**Objetivo:** Implementar a funcionalidade de marcar uma tarefa como concluída ou não concluída. 

**Especificações:** 
* Adicione uma opção para que o usuário possa marcar ou desmarcar uma tarefa como concluída diretamente na lista de tarefas. 
* Visualmente, diferencie as tarefas concluídas das não concluídas (por exemplo, com um estilo de texto riscado ou ícone de check). 
* Use o Provider para armazenar o estado de conclusão de cada tarefa. 




