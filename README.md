
# Obtencao_de_Noticias_da_Web_e_Filtragem_Utilizando_Transformers_e_Similaridade_dos_Cossenos

#### Aluno: [Andrius Lopes do Nascimento / Yasmin Costa e Silva Teixeira](https://github.com/Andrius-Lona/Andrius-Lona)
#### Orientador: [Felipe Borges](https://github.com/FelipeBorgesC) e [Leonardo Alfredo Forero Mendoza](https://github.com/leofome8)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

Este trabalho teve por objetivo obter todas as notícias presentes no site https://www.gov.br/mme/pt-br/assuntos/noticias , aplicar tratamento sobre os dados coletados e efetuar a filtragem das notícias relacionadas ao universo dos combustíveis. As notícias filtradas são obtidas mediante a comparação do nível de similaridade dos cossenos entre o título de cada notícia e o conjunto de palavras definidas como alvos de busca.

### 1. Introdução

Atualmente há uma grande quantidade de informação relacionada ao universo dos combustíveis disponível no meio digital. A pesquisa e separação de notícias cujo conteúdo apresenta relevância expressiva consome significativa quantidade de hora-homem trabalhada, quando o ser humano efetua a busca das notícias de maneira manual .
Este trabalho apresenta um método automatizado, eficiente e veloz cujo resultado é a obtenção das notícias com elevado grau de qualidade e relevância no tocante ao referido conteúdo.
A obtenção das informações filtradas foi concebida através de um script elaborado em Python.

### 2. Modelagem

O site https://www.gov.br/mme/pt-br/assuntos/noticias foi utilizado como fonte para obtenção de notícias relacionadas ao mundo dos combustíveis. Para obter os dados do site foram aplicadas técnicas de raspagem de dados. Posteriormente houve o tratamento das informações e a geração de uma de uma tabela de notícias, contendo: o título, a descrição, a data e o link de cada notícia presente em cada página existente no site.
Foi gerada uma lista de palavras e frases consideradas de elevada relevância no cenário de combustíveis (lista de palavras chave). De posse da tabela de notícias e da lista de palavras chave, foi aplicada a filtragem das notícias utilizado o modelo de aprendizado Transformer e a similaridade dos cossenos. Através da semelhança dos cossenos foi possível analisar o nível de proximidade entre a lista de palavras chave e o título das notícias obtidas do site. O nível de similaridade foi definido de maneira empírica. No script em Python, diferentes valores de similaridade entre o conteúdo da lista de palavras chave e as notícias provenientes do site foram analisados, verificando suas relações semânticas.


### 3. Resultados

Foram percorridas mais de 3200 notícias presentes no site e uma tabela de notícias com as informações relevantes  relacionadas ao universo dos combustíveis foi gerada. Uma visualização  filtrável das notícias relacionadas ao mundo dos combustíveis foi gerada usando o Power BI. 

### 4. Conclusões

Este trabalho teve por objetivo obter todas as notícias presentes no site https://www.gov.br/mme/pt-br/assuntos/noticias.
Através da comparação, nota-se um elevado nível de similaridade semântica entre as notícias filtradas e a lista de palavras chave.
O script elaborado permite que o tempo de busca, tratamento e estruturação da tabela de notícias filtradas seja ínfimo, quando comparado ao mesmo trabalho executado de maneira manual pelo ser humano. 

---

Matrícula: 201.110.660
            / 201.110.523 

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*





