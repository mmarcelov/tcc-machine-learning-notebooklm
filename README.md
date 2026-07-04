# Caderno de Pesquisa com NotebookLM
## Aplicação de Técnicas de Aprendizagem de Máquina para Análise Exploratória e Preditiva de Conjuntos de Dados

> Projeto desenvolvido como parte do desafio da DIO utilizando o NotebookLM como ferramenta de apoio à pesquisa científica e organização de conhecimento.

---

## Sobre o Projeto

Este repositório documenta o uso do **NotebookLM** como ferramenta de apoio aos estudos e à pesquisa para o desenvolvimento do Trabalho de Conclusão de Curso (TCC).

O objetivo é utilizar Inteligência Artificial para organizar referências bibliográficas, resumir conteúdos científicos, comparar metodologias e estruturar conhecimentos relacionados à área de **Machine Learning aplicado à Ciência de Dados**.

Além de atender ao desafio proposto pela DIO, este repositório servirá como material de consulta durante o desenvolvimento do TCC.

---

# Objetivos

- Estudar conceitos fundamentais de Machine Learning.
- Organizar referências bibliográficas.
- Explorar funcionalidades do NotebookLM.
- Testar estratégias de Engenharia de Prompts.
- Produzir um miniguia de revisão.
- Apoiar a construção da fundamentação teórica do TCC.

---

# Tema de Pesquisa

**Aplicação de Técnicas de Aprendizagem de Máquina para Análise Exploratória e Preditiva de Conjuntos de Dados**

Principais assuntos estudados:

- Machine Learning
- Ciência de Dados
- Análise Exploratória de Dados (EDA)
- Pré-processamento
- Engenharia de Atributos
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Avaliação de Modelos

---

# Fontes Utilizadas

As seguintes referências foram adicionadas ao NotebookLM:

| Fonte | Tipo |
|--------|------|
| Projeto de Pesquisa do TCC | PDF |
| Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow - Aurélien Géron | Livro |
| Introduction to Machine Learning - Ethem Alpaydin | Livro |
| Machine Learning - Tom Mitchell | Livro |
| Artigos científicos da ACM relacionados ao tema | PDF |

---

# Engenharia de Prompts

## Prompt 1

> Explique as diferenças entre Random Forest, XGBoost e SVM considerando problemas de classificação em dados tabulares.

### Objetivo

Compreender quando utilizar cada algoritmo.

### Resultado

O NotebookLM apresentou uma comparação destacando vantagens, limitações e principais casos de uso.

---

## Prompt 2

> Compare as metodologias utilizadas nos artigos fornecidos.

### Objetivo

Identificar padrões metodológicos para o desenvolvimento do TCC.

### Resultado

Foi possível observar que praticamente todos os trabalhos seguem um pipeline composto por:

- Coleta de dados
- Pré-processamento
- Engenharia de atributos
- Treinamento
- Avaliação
- Discussão dos resultados

---

## Prompt 3

> Quais conceitos aparecem em comum entre todas as referências?

### Resultado

Os principais conceitos encontrados foram:

- Aprendizado Supervisionado
- Engenharia de Atributos
- Avaliação de Modelos
- Generalização
- Qualidade dos Dados

---

## Prompt 4

> Gere um resumo da Fundamentação Teórica.

### Resultado

Foi gerado um resumo organizado por tópicos, facilitando a revisão.

---

# Dificuldades Encontradas

Durante a utilização do NotebookLM foram observados alguns desafios:

- Prompts muito amplos produziram respostas superficiais.
- Perguntas específicas geraram respostas mais completas.
- Solicitar comparações entre autores aumentou significativamente a qualidade das respostas.
- O NotebookLM apresentou melhor desempenho quando todas as referências estavam previamente carregadas.

---

# Miniguia de Estudos

## Machine Learning

Área da Inteligência Artificial que permite aos computadores aprender padrões a partir de dados sem serem explicitamente programados.

---

## Tipos de Aprendizado

### Supervisionado

Utiliza dados rotulados para realizar previsões.

Exemplos:

- Classificação
- Regressão

---

### Não Supervisionado

Agrupa dados semelhantes sem utilizar rótulos.

Exemplo:

- Clusterização

---

### Aprendizado por Reforço

O algoritmo aprende através de recompensas.

---

## Pipeline de um Projeto de Machine Learning

1. Coleta dos Dados

2. Limpeza

3. Análise Exploratória

4. Engenharia de Atributos

5. Treinamento

6. Avaliação

7. Interpretação

---

# Glossário

| Conceito | Definição |
|-----------|-----------|
| Dataset | Conjunto de dados |
| Feature | Variável utilizada pelo modelo |
| Label | Variável alvo |
| Overfitting | Modelo especializado demais nos dados de treino |
| Underfitting | Modelo incapaz de aprender padrões |
| Recall | Capacidade de encontrar casos positivos |
| Precisão | Proporção de previsões corretas entre os positivos |
| F1-score | Média harmônica entre Precisão e Recall |

---

# Prompts Reutilizáveis

### Revisão Bibliográfica

```
Compare os principais conceitos apresentados pelos autores.
```

---

### Escrita Científica

```
Resuma este artigo mantendo linguagem acadêmica.
```

---

### Metodologia

```
Quais etapas metodológicas são utilizadas neste estudo?
```

---

### Comparação

```
Compare os algoritmos apresentados considerando desempenho, interpretabilidade e custo computacional.
```

---

### Revisão

```
Crie um resumo em tópicos para revisão antes da escrita do TCC.
```

---

# Próximos Passos

- [ ] Escolher o dataset definitivo
- [ ] Realizar a EDA
- [ ] Implementar os modelos
- [ ] Comparar métricas
- [ ] Escrever os resultados
- [ ] Atualizar este repositório durante o desenvolvimento do TCC

---

# Ferramentas

- NotebookLM
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Kaggle
- GitHub

---

# Autor

**Marcelo Vitor Martins Paiva**

Graduando em Sistemas de Informação — PUC Minas

Projeto desenvolvido como parte do desafio da DIO e utilizado como apoio ao Trabalho de Conclusão de Curso.
