# Enem & Inteligência Artificial
## Implementando algoritmo para classificação do assunto das questões

Repositório com implementação de um classificador do assunto de questões do Enem (Exame Nacional do Ensino Médio) a partir do seu texto.


## Contents

### Pasta 📁**notebooks**
- **Enem_obter_questões.ipynp**  
Responsável por automaticamente coletar as provas do Enem a partir do site do Inep e segmentar cada pdf nas questões que o compõem. Também atribui a cada questão um dos 5 rótulos possíveis: UNDEFINED, Ciências da Natureza, Ciências Humanas, Linguagens e códigos e Matemática.
- **Enem_NLP.ipynb**  
Notebook englobando todos os aspectos da criação de um algoritmo de Machine Learning para classificação textual: Natural Language Processing, Exploratory Data Analysis, Data Visualization, Machine Learning.

<p align="center">
  <img src="https://github.com/jaumpedro214/enem-nlp-classification/blob/main/imgs/wordcloudenem.png" width="350" title="hover text">
</p>

### Pasta 📁**data**

Dataset contendo questões de aplicações do Enem de 2011 até 2020, coletadas a partir do site do Inep. Contém ~4000 questões classificadas entre as 4 grandes áreas do conhecimento.

| Feature | Descrição  | Tipo  |
|---|---|---|
|  enunciado |  Enunciado da questão e alternativas |  string |
|  area |  Um dos rótulos: UNDEFINED, Ciências da Natureza, Ciências Humanas, Linguagens e códigos e Matemática | string  |
