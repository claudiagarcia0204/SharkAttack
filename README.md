<h1 align="center"><img src="https://bit.ly/2VnXWr2" width="60">

# Projeto SharkAttack


![image](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
<br/>
Status do Projeto: Em desenvolvimento:warning:
___
![GitHub top language](https://img.shields.io/github/languages/top/claudiagarcia0204/SharkAttack)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/claudiagarcia0204/SharkAttack)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/claudiagarcia0204/SharkAttack)
![GitHub last commit](https://img.shields.io/github/last-commit/claudiagarcia0204/SharkAttack)

# Objetivo do projeto
O projeto teve como objetivo apresentar técnicas de manipulação para ler um CSV, utilizando diferentes métodos de limpeza de dados no DataFrame. 

___
# Métodos
Lista com métodos:

* Manipulação de dados
* Limpeza de dados
* Cálculos no DataFrame
* Filtrar
* Agrupamento

___
# Tecnologias
Lista com tecnologias utilizadas:

* Python
* Pandas
* Regex
* Pd.loc
* Pd.pivot_table
* Pd.str.findall
* Pd.str.contains
* Pd.dropna
* Pd.expressões regulares
* Pd.numpy

___
# Descrição do Projeto
O projeto utilizou como base a tabela de incidentes de ataque de tubarão compilada pelo Arquivo Global de Ataque de Tubarão. Os dados foram baixados através do site do Global Shark Attack https://www.kaggle.com/teajay/global-shark-attacks/version/1
Os métodos utilizados, descritos acima, quis responder a questão sobre: Quais tipos de atividades levam homens e mulheres a sofrerem maiores números de ataques de tubarão.

___
## Passos
Com base no DataFrame inicial os dados totais foram de  25723 linhas / 24 colunas sendo que:
* 488.276 dos dados (entre linhas e colunas) estavam apresentados como nulos, que compreendem quase 65% do total de linhas. Essas linhas podem ser eliminadas com o método pandas.DataFrame.dropna para reduzir o tamanho geral do conjunto de dados.

* Foram removidos aproximadamente 1/4 dos arquivos duplicados - Utilizando o .duplicated (numerador / denominador)

* As colunas que não estavam relacionadas diretamente a questão a ser respondida, foram removidas

* O total de pessoas envolvidas nos acidentes por sexo (mem e women) inicialmente era de 6312. Após a limpeza de dados, considerando valores com dados ('N' e '.') foi atualizado por 6308 ('F' = 637 / 'M' = 5096)

* O total de Atividades envolvidas nos acidentes foi de 5733 distribuida em diversas subcategorias. Após a análise, para limitador de categorais, foram renomeados e listados apenas 9 categorias principais.

___
## Conclusão
Considerando os dados levantados pela coluna "Sexo" e "Atividades", foi possivel verificar em relação aos casos de acidentes:

* Wading - 32,02 % dos acidentes aconteceram com pessoas que estavam 'Atravessando, passando' pelas praias, sendo: 67,79 % envolvem homens e 32,08 % envolve mulheres

* Standing - 24,02 % dos acidentes aconteceram com pessoas que estavam 'Em pé na água', sendo: 75,81 % envolvem homens e 24,06 % envolve mulheres

* Rowing - 22,73 % dos acidentes aconteceram com pessoas que estavam 'Remando' sendo: 76,19 % envolvem homens e 22,97 % envolve mulheres

* Swimming - 16,49 % dos acidentes aconteceram com pessoas que estavam 'Nadando ', sendo: 83,49 % envolvem homens e 16,49 % envolve mulheres

* Bathing - 11,89 % dos acidentes aconteceram com pessoas que estavam 'Banhando', sendo: 88,04 % envolvem homens e 11,89 % envolve mulheres

* Surfing - 6,15 % dos acidentes aconteceram com pessoas que estavam 'Surfando', sendo: 93,84 % envolvem homens e 6,15 % envolve mulheres

* Diving - 5,48 % dos acidentes aconteceram com pessoas que estavam 'Mergulhando', sendo: 94,50 % envolvem homens e 5,48 % envolve mulheres 

* Fishing - 2,77 % dos acidentes aconteceram com pessoas que estavam 'Mergulhando', sendo: 97,21 % envolvem homens e 2,77 % envolve mulheres 

* Other - 15,19 % dos acidentes aconteceram com pessoas que estavam 'Fazendo outras atividades', sendo: 84,79 % envolvem homens e 15,19 % envolve mulheres 

___
## Conclusão final
Em uma análise inicial, foi possível verificar que os homens, na totalidade dos acidentes , são mais propensos a acidentes com ataques de tubarões.

A análise também apresentou informações que podem (a principio) demonstrar que atividades como Pesca; Mergulho; Surf detém uma diferença significativa com relação a porcentagem (94%, 89%, 87% maior que os incidentes com mulheres na mesma atividade).
___

Contato
* linkedin: www.linkedin.com/in/ claudia-garcia0204
* github: https://github.com/claudiagarcia0204

