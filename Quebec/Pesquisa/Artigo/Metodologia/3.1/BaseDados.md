Com o intuito de extrair informações sobre a localização dos criminosos, utilizamos três bases de dados disponíveis no sitChicago Data Portal: a base Sex Offenders, a base de Crimes e a base de Parks.

A base Sex Offenders é uma lista de agressores sexuais que residem em Chicago. Porém, por questões de privacidade, os endereços são exibidos em níveis de blocos para não especificar a localização exata dos mesmos. Essa base é atualizada diariamente e continha, no momento da realização deste trabalho, 2.775 linhas com 10 atributos prévios, conforme descrito na Tabela [1].

tabala aki

Já a base de Crimes é composta pelos crimes ocorridos em Chicago desde 2001 até os dias atuais. A estrutura dessa base pode ser vista na imagem [2], onde todos os atributos presentes estão destacados, além de sua dimensão. Como alguns locais foram em residências, os dados são colocados em regiões para preservar a privacidade das vítimas e dos próprios criminosos.

tabala aki

A base de Parks, por sua vez, informa o perímetro de todos os parques contidos na cidade de Chicago, incluindo sua localização e dimensão, conforme apresentado na imagem [3]. Diante dessas informações, foram realizados pré-processamentos nos dados e bases para remover informações desnecessárias e viabilizar o treinamento do modelo.


tabala aki

O foco do trabalho foi identificar grupos de criminosos sexuais com base em suas informações de localização e outros aspectos . Para isso, utilizamos os dados dessas bases, removendo informações irrelevantes e aplicando técnicas de pré-processamento.