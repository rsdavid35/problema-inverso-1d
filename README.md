# Solução de Problema Inverso de Transferência de Calor

Este repositório contém o código para a solução do problema inverso de transferência de calor, configurado para processar os dados do arquivo `data.csv`.

## Funcionalidades Principais

* **Problema Inverso:** Solução direta implementada para a base de dados em `data.csv`.
* **Transferência de Calor Unidimensional (`fdm()`):** A função `fdm()` (Método das Diferenças Finitas) foi projetada para ser modular. Ela pode ser empregada em casos gerais de transferência de calor 1D onde:
  * Uma parede está sujeita a uma condição de temperatura prescrita.
  * A outra parede sofre convecção.

## Uso do Código

O código é rico em comentários detalhados. Isso foi feito para facilitar a compreensão lógica e permitir que você utilize o script de forma integral ou extraia partes (uso parcial) para outros modelos numéricos.

## Documentação e Aspectos Teóricos

Para entender o embasamento matemático e os aspectos teóricos que fundamentam esta implementação, consulte a documentação oficial do projeto:

📄 **[`L2C_Trabalho_Final_David_Rodrigues.pdf`](./L2C_Trabalho_Final_David_Rodrigues.pdf)**
