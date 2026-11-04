# 📚 Biblioteca Digital
Projeto acadêmico de sistema desktop para gerenciamento de biblioteca, parte do Projeto Integrador II do curso de Análise e Desenvolvimento de Sistemas pelo Senac-RS. Desenvolvido com Java, Java Swing e MySQL, e classes DAO para organizar as operações de persistência dos dados.

## 🛠️ Tecnologias Utilizadas
- Linguagem: Java
- Interface gráfica: Java Swing
- Banco de dados: MySQL com JDBC

## 🎯 Objetivo do Software
Desenvolver um sistema desktop que facilite o gerenciamento de uma biblioteca, permitindo controlar o acervo, os usuários e as operações de empréstimo e devolução de livros.

## 📝 Funcionalidades
*🔐 Autenticação e controle de acesso*
  - Autenticação de usuários;
  - diferenciação entre usuários comuns e administradores;
  - controle de acesso às funcionalidades conforme o perfil.

*📖 Gerenciamento de livros*
  - Cadastro de livros;
  - listagem e filtragem do acervo por título, autor ou ISBN;
  - controle da disponibilidade dos livros.

*👥 Gerenciamento de usuários*
  - Cadastro de usuários;
  - definição de perfis de acesso;
  - listagem e filtragem de usuários cadastrados.

*🔄 Gerenciamento de empréstimos*
  - Registro de empréstimos de livros;
  - registro de devoluções;
  - consulta e filtragem do histórico de empréstimos.

## ⚙️ Configuração e execução
Pré-requisitos:
- Java JDK instalado.
- MySQL Server instalado e em execução.
- IDE compatível com projetos Java, como NetBeans.
- Driver JDBC do MySQL.

Antes de executar:
- Execute o script em biblioteca_db.
- Configure as credenciais de acesso ao banco na classe ConexaoDB, conforme seu ambiente local.

## 👨‍💻 Autor
- Guilherme de Carvalho Gois
