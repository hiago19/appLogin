# appLogin

**appLogin** é uma aplicação Python desenvolvida com o framework Kivy para fornecer funcionalidades básicas de autenticação de usuários, incluindo login e criação de conta.

## Sobre o Projeto

O projeto **appLogin** foi desenvolvido para demonstrar o uso do framework Kivy em Python para criar uma interface de usuário simples para autenticação de usuários. Ele permite que os usuários criem contas com nome, email e senha, façam login em suas contas e visualizem informações da conta.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **Database.py**: Contém a classe `DataBase`, responsável por manipular o arquivo de banco de dados `users.txt`, que armazena informações dos usuários, como email, senha, nome e data de criação da conta.
- **Main.py**: Contém o código principal da aplicação, onde a interface do usuário é definida usando o Kivy e a lógica de autenticação de usuários é implementada.
- **mk.kv**: Este arquivo contém a estrutura de design da interface do usuário, definida usando a linguagem de marcação Kivy. Ele descreve a aparência e o comportamento das diferentes telas do aplicativo.
- **users.txt**: Arquivo de banco de dados que armazena as informações dos usuários cadastrados.

## Tecnologias Utilizadas

O projeto foi desenvolvido em Python, utilizando o framework Kivy para criação da interface gráfica.

## Rodando Localmente

Para executar o projeto localmente, siga estas etapas:

1. Certifique-se de ter o Python instalado em sua máquina.

2. Instale o framework Kivy executando o seguinte comando:

   ```bash
   pip install kivy
   ```

3. Clone o repositório para sua máquina local:

   ```bash
   git clone https://github.com/hiago19/appCalculadora.git
   ```

4. Navegue até o diretório do projeto:

   ```bash
   cd appCalculadora
   ```

5. Execute o arquivo `Main.py`:

   ```bash
   python Main.py
   ```

6. A aplicação será iniciada e estará pronta para uso.

## Funcionalidades

- **Criar Conta**: Os usuários podem criar uma nova conta fornecendo um nome, um email e uma senha válidos.
- **Login**: Os usuários podem fazer login em suas contas usando o email e a senha cadastrados.
- **Visualizar Informações da Conta**: Os usuários autenticados podem visualizar informações da conta, como nome, email e data de criação.

## Demonstração

Aqui está uma demonstração visual da aplicação:

![Main Window](https://github.com/hiago19/appLogin/assets/81202387/d803af29-4462-42d6-a938-5534f5cf620b)



![Create Account](https://github.com/hiago19/appLogin/assets/81202387/58e0aca4-3f52-45eb-bf88-b1525fb3c487)


![Login](https://github.com/hiago19/appLogin/assets/81202387/7e73a48f-b840-47ff-b7f2-3f6f7ad3b052)
