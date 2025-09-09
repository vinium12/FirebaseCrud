# 🟢 AppFirebaseCRUD

Este projeto demonstra a integração de um aplicativo Android moderno, desenvolvido em **Kotlin** e **Jetpack Compose**, com **Firebase Cloud Firestore**. Ele inclui autenticação de usuários e um sistema CRUD de produtos.

---

## 🔹 Visão Geral do Projeto

O aplicativo permite:

- Cadastro e login de usuários;
- Gerenciamento de produtos (CRUD);
- Atualização em tempo real dos dados armazenados no Firebase.

💡 **Objetivo:** Fornecer um exemplo completo de integração entre Android e Firebase, incluindo navegação entre telas, autenticação e operações CRUD.

---

## 🛠 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| 🟪 Kotlin | Linguagem principal do projeto |
| 📱 Android SDK | Desenvolvimento de apps Android |
| ☁️ Firebase Firestore | Banco de dados NoSQL em tempo real |
| 🎨 Jetpack Compose | Interface moderna e declarativa |
| 🔀 Compose Navigation | Gerenciamento de telas e navegação |
| ⚙️ Gradle | Gerenciamento de dependências e build |

---

## 📂 Estrutura do Projeto

* **`MainActivity.kt`**:  
  Ponto de entrada do aplicativo. Configura o **NavHost**, que gerencia a navegação entre as telas de login, registro, home e CRUD.

  * **`LoginScreen()`**: Tela para login de usuários, com validação das credenciais no Firestore.
  * **`RegisterScreen()`**: Tela para cadastro de novos usuários e armazenamento de dados no Firestore.
  * **`HomeScreen()`**: Tela inicial exibida após o login. Permite listar registros do banco e navegar para CRUD.
  * **`CrudScreen()`**: Tela para realizar operações CRUD em uma coleção de produtos.


---

## 📌 Funcionalidades

### 👤 Autenticação de Usuários
- Registro com nome, apelido, email, senha e telefone.
- Login verificando credenciais no Firestore.
- Logout com retorno à tela de login.

### 📝 CRUD de Produtos
- **Create**: Adiciona produtos no Firestore.
- **Read**: Lista produtos em tempo real.
- **Update**: Edita produtos existentes.
- **Delete**: Remove produtos do banco de dados.

### 🔄 Navegação
- Fluxo dinâmico entre telas usando **Jetpack Compose Navigation**.
- Transição suave entre login, registro, home e CRUD.

---

## 🎨 Interface e Componentes

### Campos de Texto
- `CustomDarkTextField`: TextField estilizado com tema escuro.
- Suporte a senha oculta, ícones e cores personalizadas.

### Botões
- Botões arredondados com cores consistentes ao tema.
- Botões de ação: salvar, atualizar, editar, excluir, voltar.

---

## 🖼 Imagens (adicione suas capturas de tela aqui)

<div style=''>
  <img width="250" alt="image" src="https://github.com/user-attachments/assets/ab353af6-d2da-4bd0-8ff3-219a96944369" />
  <img width="250" alt="image" src="https://github.com/user-attachments/assets/02cb99a7-975a-4934-855f-a319298318bc" />
  <img width="250" alt="image" src="https://github.com/user-attachments/assets/b1ea44e5-3632-41ea-aa05-dfaa0e24c4e9" />
  <img width="250" alt="image" src="https://github.com/user-attachments/assets/cbf7fbf7-1bef-46c5-93be-0bee110155bd" />
  
</div>


