# Dados
Os dados que são carregados no preprocessador não estão presentes no repositório no github por serem muito pesados. Estão salvos no armazenamento em nuvem do autor (google drive) e podem ser obtidos mediante requisição.


# Preprocessador

1. Remove horários anômalos (horários que não são múltiplos de 10 minutos)
2. Preenche os missing values com a seguinte sequência: interpolate linear, bfill e ffill.
3. Devido a uma grande quantidade de dados faltantes, remove todas as estações que não pertencem às seguintes listas:
* Rio: 143, 283, 413, 563, 629, 1000580, 1000610, 1000958
* Chuva: 143, 283, 413, 511, 514, 563, 629, 1000500, 1000510, 1000868
A análise do percentual de dados faltantes foi feita em planilha separada.
4. Remoção da estação 143, pois visualmente apresenta problemas severos no ano de 2021 e 2022


# Qualification
Esse foi o notebook usado para gerar os dados da qualificação

