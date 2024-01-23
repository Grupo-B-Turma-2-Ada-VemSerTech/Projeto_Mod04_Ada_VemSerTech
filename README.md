# Projeto_Mod04_Ada_VemSerTech
Repositorio para o desenvolvimento do projeto 4 Grupo B - Técnicas de Programação I

# Equipe:
- Adriely
- Amanda
- Daniel
- Lorrany
- Ricardo
- Thiago

# Análises de dados em Python dos microdados do ENEM 2022

Este repositório contém um conjunto de scripts em Python para realizar análises de dados dos microdados do ENEM 2022.

Primeiramente foi realizado uma limpeza de colunas do arquivo original para facilitar o manuseio do arquivo, deixando-o mais leve. O processo realizado está disponível no script entitulado ``limpeza_dados.ipynb``. Devido o github não suportar o carregamento dos dados originais, ele não está presente no repositório, porém pode ser adquirido no site do INEP:
[Microdados Enem 2022](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)

Para usar os scripts, você precisará instalar os seguintes pacotes Python:

- ``pandas``
- ``geopandas``
- ``matplotlib``


## Análises Realizadas

1- Análise dos presentes, ausentes e eliminados nos dois dias de prova.

2- Análise do Diagrama de Caixa das Notas por Bloco de Conhecimento.

3- Análise da distribuição de acordo com o sexo na realização da prova (M-masculino / F-Feminino)

4- Análise da distribuição de acordo com o Estado Civil.

5- Análise da distribuição de acordo com a Raça/Cor.

6- Análise da distribuição de acordo com a Situação de Conclusão Escolar.

7- Análise da distribuição de acordo com o Tipo Escolar (Pública ou Privada). Analisamos a média das notas de cada disciplina pelo tipo de escola.



## Conclusões

1- 

2- Os outliers inferiores das provas objetivas ocorreram quando o aluno zerou a prova.
- A redação foi a prova com a maior dispersão de dados.
- As notas de ciências humanas tem mediana próxima a média, isso significa que a distribuição dos dados é simétrica. A média próxima da mediana significa que a maioria dos alunos teve notas semelhantes. Ou seja, não houve muitos alunos com notas muito altas ou muito baixas.
- Nas notas da prova de linguagem e código, podemos observar que o tamanho da caixa é menos, isso indica que a maioria dos alunos teve notas semelhantes, próximo a mediana.
- Na prova de matemática, podemos observar maior dispersão dos dados maiores que a mediana em relação as notas menores que a mediana.

3- Podemos observar que a maioria dos inscritos são do sexo feminino, o que está de acordo com as estatística da população brasileira.

4-

5-

6-

7- Concluímos que estudantes de escolas privadas obtiveram uma nota média maior no ENEM 2022 em comparação com os estudantes de escolas públicas.
Essa disparidade pode indicar diferenças nos recursos educacionais que impactam o desempenho acadêmico.