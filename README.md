# Projeto-em-CSharp
Formulário em C# e Banco de dados SQL.
# 🎵 Biblioteca de Música - CRUD Desktop

Uma aplicação desktop para gerenciamento de acervo musical. O projeto implementa um sistema completo de **CRUD** (Create, Read, Update, Delete) com uma interface gráfica customizada e temática inspirada no universo dos discos de vinil e fitas cassete.

## 🚀 Funcionalidades

O sistema foi projetado para ser intuitivo e oferece as seguintes operações de gerenciamento:

* **Cadastrar (Create):** Permite a inserção de novas faixas informando Título, Artista, Álbum, Gênero e Duração. O sistema gera automaticamente o código identificador.
* **Listar (Read):** Exibição em tempo real de todas as músicas cadastradas através de uma tabela organizada na parte inferior da interface.
* **Editar (Update):** Ao selecionar uma música na tabela, os dados são recarregados nos campos de entrada para permitir alterações rápidas com validação.
* **Excluir (Delete):** Remoção definitiva de registros selecionados diretamente do banco de dados/lista local.

---

## 💻 Demonstração do Fluxo de Uso

No vídeo de demonstração do projeto, é possível observar o ciclo completo de uso da aplicação:

1.  **Inserção:** O usuário preenche os dados da faixa *"Spring Day"* do grupo *"BTS"* e clica em `Salvar`, recebendo feedback de sucesso.
2.  **Modificação:** O gênero da música é atualizado de *"Pop"* para *"Pop/Hip-Hop"* utilizando a função `Editar`.
3.  **Remoção:** O registro é selecionado e apagado do sistema de forma segura através da função `Excluir`.

---

## 🎨 Design e Interface

A interface do usuário (UI) conta com uma estilização personalizada que foge do padrão convencional do sistema operacional, trazendo:
* Banner temático retrô de estúdio musical (*Biblioteca de Música.*).
* Paleta de cores em tons pastéis e roxos.
* Caixas de diálogo nativas (Pop-ups) para confirmação de ações, garantindo que o usuário tenha certeza das operações realizadas.

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **Linguagem:** [CSharp Visual Studio .Net Framework]
* **Interface Gráfica:** [Sua Biblioteca de GUI]
* **Arquitetura:** Orientação a Objetos (POO) com manipulação de eventos e estados de tabelas dinâmicas.
