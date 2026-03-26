# Sistema de Extração de Metadados - Node.js

**Aluno:** Hugo Oliveira  
**Professor:** Vinicius Heltai
**Materia:** DEV WEB III (Desenvolvimento Web III)
**Atividade:** projeto 02 

##  Descrição do Projeto

Este projeto consiste em um sistema desenvolvido em Node.js (Metadados) com o objetivo de realizar a leitura e processamento de arquivos na extensão .md, extraindo referências (links) utilizando Expressões Regulares (RegEx).

O sistema lê um arquivo contendo links estruturados no formato MD e extrai automaticamente o nome da referência e sua respectiva URL.

utilizando o CHALK para mostrar com sistema de cores
**link no arquivo .md não são reais e o teste de validação de cores é aleatorio**
**verde significa que o link esta funcional (hipoteticamente)**
**vermelho que esta dando erro**
**amarelo que deu um erro com algum numero Exemplo 202**

##  Funcionamento do projeto

- Realiza a leitura assíncrona de um arquivo `.md` utilizando o módulo `fs/promises`.
- Utiliza uma expressão regular para identificar e extrair links no formato:
  
