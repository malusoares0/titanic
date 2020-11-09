O projeto Titanic contém arquivos com dados dos tripulantes
do navio Titanic que naufragou em 1912.

 
---------
train.csv - contém os detalhes de um subconjunto de passageiros a bordo 
(891 passageiros, para ser exato - onde cada passageiro obtém uma linha 
diferente na tabela). 


---------
VARIABLE DESCRIPTIONS
Pclass 	 | Classe dos passageiros
survival | Sobrevivente (0 = não; 1 = sim)
name 	 | Nome
sex 	 | Sexo
age 	 | Idade
sibsp	 | Número de irmãos/cônjuges a bordo
parch 	 | Número de pais/filhos a bordo
ticket	 | Número do bilhete
fare	 | Tarifa (£ libras)
cabin	 | Número da cabine
embarked | Porto de embarcação (C = Cherbourg; Q = Queenstown; S = Southampton)
boat	 | Lifeboat
body	 | Body Identification Number
home.dest| Home/Destination


---------
EXPLICAÇÃO SOBRE TRAIN E TEST
como não vou fazer nenhuma previsão, mas só vou analisar o df, 
então é melhor juntar train e test. Caso eu fosse fazer algum tipo de 
previsão, aí sim poderia mantê-los separados.