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

* **`pages/`** (telas principais):
  * **`LoginScreen.kt`**: Tela para login de usuários, com validação das credenciais no Firestore.
  * **`RegisterScreen.kt`**: Tela para cadastro de novos usuários e armazenamento de dados no Firestore.
  * **`HomeScreen.kt`**: Tela inicial exibida após o login. Permite listar registros do banco e navegar para CRUD.
  * **`CrudScreen.kt`**: Tela para realizar operações CRUD em uma coleção de produtos.


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


