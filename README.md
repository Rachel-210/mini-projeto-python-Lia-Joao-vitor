# 💻 Mini-Projetos Python: Controle de Estoque e Gestão de Notas

Este repositório contém dois mini-projetos desenvolvidos em Python como atividade de complemento de nota para a disciplina de **Programação I - Python**.

Os projetos focam na aplicação de conceitos de **Estruturas de Repetição** (`while`, `for`) e **Estruturas de Dados** (Listas, Dicionários, Tuplas e Sets) em cenários práticos.

## 🤝 Autores

Este projeto foi desenvolvido em dupla por:

* **Lia Rachel Ferreira De Sousa**
* **João Vitor Rodrigues**

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Estruturas:** Listas, Dicionários, Tuplas e Sets.
* **Ferramenta de Código:** Google Colab

---

## 📦 Projeto 1: Sistema de Cadastro de Produtos (Mini Controle de Estoque)

Sistema simples para informatizar o controle de produtos de uma pequena loja.

### 🎯 Estruturas de Dados Utilizadas

* **Lista:** Armazena todos os dicionários de produtos.
* **Dicionário:** Cada produto é armazenado com chaves como `"codigo"`, `"nome"`, `"preco"` e `"quantidade"`.
* **Set (Conjunto):** Utilizado para controlar os códigos de produtos já cadastrados e evitar duplicatas.
* **Tupla:** Contém as categorias de produtos disponíveis.

### 📝 Menu e Opções

O sistema deve permanecer em execução até que a opção de saída seja escolhida.

| Opção | Funcionalidade |
| :---: | :------------- |
| **1** | Cadastrar produto |
| **2** | Listar produtos |
| **3** | Buscar produto |
| **4** | Atualizar produto |
| **5** | Excluir produto |
| **0** | **Sair** |

---

## 🧑‍🎓 Projeto 2: Sistema de Controle de Alunos e Notas

Sistema para registrar alunos, armazenar notas, calcular médias e gerar um relatório geral de desempenho da turma.

### 🎯 Estruturas Utilizadas
* **Lista:** Usada dentro da função cadastrar_aluno() para armazenar as notas digitadas pelo usuário:

  notas = []

Cada nota é adicionada com notas.append(nota).
* **Dicionário:** Armazena todos os alunos cadastrados.

  alunos = {}

Cada chave é o nome do aluno, e o valor é outro dicionário com as informações dele
* **Set (Conjunto):** Representado por nomes_cadastrados, tem a função de evitar que dois alunos com o mesmo nome sejam cadastrados mais de uma vez.
* **Estrutura de repetição for:** Empregada no cadastro de notas e nos relatórios, percorre listas e dicionários para exibir ou processar informações de todos os alunos.

* **Estrutura condicional if / else:** Responsável pela validação e controle lógico do sistema, como verificar se um aluno já está cadastrado ou definir se foi aprovado ou reprovado.

* **Estrutura de repetição while True:** Usada para manter o menu principal em execução contínua até que o usuário escolha encerrar o programa.

* **Funções (def):** Organizam o código em partes independentes e reutilizáveis, separando as lógicas de cadastro, consulta, listagem, relatórios e controle de navegação.

* **Comando exit():** Finaliza o sistema de forma controlada, encerrando a execução quando o usuário decide sair do programa.

### 📝 Menu e Opções

O sistema apresenta 7 opções no menu principal:

| Opção | Funcionalidade | 
| :---: | :------------- | 
| **1** | Cadastrar aluno | 
| **2** | Registrar Notas | 
| **3** | Listar Alunos e Médias |
| **4** | Buscar Aluno |
| **5** | Mostrar Aporvados e Reprovados |
| **6** | **Relatório Geral** | 
| **0** | **Sair** | 
