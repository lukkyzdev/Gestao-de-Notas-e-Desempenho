# <img align="center" alt="Python" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"> Gestão de Notas e Desempenho | Python Core

Um sistema interativo de terminal desenvolvido em Python puro para processar, validar e analisar o desempenho escolar de alunos.

O projeto foca na aplicação prática dos fundamentos da linguagem, implementando entrada de dados dinâmica, armazenamento estruturado em memória (Listas), processamento matemático e lógicas de validação.

## 🎯 Objetivo do Projeto
Construir um script automatizado que receba um volume variável de dados (notas), processe esses inputs e retorne um relatório analítico formatado. Este projeto serviu para consolidar conceitos essenciais de lógica de programação:
- Interação contínua com o utilizador (Input/Output).
- Manipulação de coleções de dados (Listas).
- Controlo de fluxo com estruturas de repetição (`while`/`for`) e condicionais (`if`/`else`).

## 🚀 Como Funciona a Lógica
O sistema opera em três fases principais de processamento:
1. **Coleta de Dados (Ingestão):** O script solicita a inserção de notas continuamente através de um laço de repetição. O utilizador encerra a coleta inserindo a *flag* de paragem `-1`.
2. **Processamento Matemático:** O algoritmo percorre a lista de valores armazenados em memória e calcula a média aritmética.
3. **Classificação e Relatório:** Com base na média gerada, o sistema aplica uma regra de negócio (Aprovado se >= 7, Reprovado se < 7) e imprime um boletim final detalhado.

## 💻 Demonstração de Uso
Abaixo, é possível visualizar a interação do utilizador via terminal, validando a inserção de dados e a geração do relatório final de aprovação:

> **Execução e Relatório Final:**
> 
> ![Código em Execução](./images/códigoemexecução.png)

> **Estrutura do Código:**
> 
> ![Código Completo](./images/códigocompleto.png)

## 📂 Acesso ao Código Fonte
O script completo com as validações e a lógica de processamento pode ser analisado no ficheiro abaixo:
- [📄 Sistema Simples de Gestão de Notas de Alunos.py](https://github.com/lukkyzdev/PROJETO-SistemaSimplesDeGestaoDeNotasDeAlunos/blob/main/Sistema%20Simples%20de%20Gestão%20de%20Notas%20de%20Alunos.py)

---
*Desenvolvido por Lucas Fontes com foco na consolidação de lógica de programação e fundamentos de Python.*
