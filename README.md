# Cadastro de Clientes Swing

Este projeto é uma aplicação desktop simples desenvolvida em Java utilizando a biblioteca **Swing** para gerenciar o cadastro de clientes. A interface gráfica permite adicionar, listar e excluir clientes de uma tabela.

## Funcionalidades

- **Adicionar Cliente**: Insere um cliente na tabela, validando campos obrigatórios (Nome e CPF) e garantindo que não sejam inseridos CPFs duplicados.
- **Excluir Cliente**: Remove o cliente selecionado na tabela, com uma confirmação prévia.
- **Tabela de Clientes**: Exibe os clientes cadastrados com Nome e CPF.

## Tecnologias Utilizadas

- **Java SE**: Linguagem de programação principal.
- **Swing**: Biblioteca para construção da interface gráfica.
- **JTable**: Componente para exibição e manipulação de dados em forma de tabela.
- **DefaultTableModel**: Utilizado para gerenciar os dados da tabela.

## Como Usar

1. Clone o repositório e importe o projeto em sua IDE favorita (NetBeans, IntelliJ, Eclipse, etc.).
2. Execute o arquivo principal `TelaPrincipal.java`.
3. Utilize os campos de texto e os botões da interface para:
   - Adicionar novos clientes com Nome e CPF.
   - Selecionar um cliente na tabela e excluí-lo.
4. O menu "Opções" possui a funcionalidade de sair da aplicação.

## Funcionalidades Extras

- **Validação de Campos**: Não permite adicionar clientes com campos vazios.
- **Validação de CPF Duplicado**: Garante que cada CPF seja único na tabela.
- **Confirmação de Exclusão**: Evita exclusões acidentais com um prompt de confirmação.

## Capturas de Tela

![image](https://github.com/user-attachments/assets/b73d4abe-ce1a-4fb8-83a1-b41c7bbc5184)


## Estrutura do Projeto


- **TelaPrincipal.java**: Arquivo principal que contém toda a lógica da aplicação.

## Próximos Passos

- Melhorar a validação do CPF com um algoritmo de validação formal (como o dígito verificador).
- Persistir os dados cadastrados em um banco de dados ou arquivo para não perder informações ao fechar a aplicação.
- Implementar busca por cliente na tabela.

---

Feito com ❤️ por [Raphael](https://github.com/rapheallima)
