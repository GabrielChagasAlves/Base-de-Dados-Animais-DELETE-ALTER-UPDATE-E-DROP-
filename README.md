# Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-
# # Exercicio com objetivo de mostrar diversas operações feitas em uma tabela de banco de dados, como alteração de nomes, inclusao de colunas de especie, alteração de cor de animais e etc..

## 1- Altere o nome do Pateta para Goofy:
#### Update animais set nome = 'Goofy' where id = 15
![Altere o nome do Pateta para Goofy;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/10458ebd-1a31-40c2-b479-29f8d7bf4ecc)
### alteração de nome do animal da tabela

## 2- Altere o peso do Garfield para 10 quilogramas:
#### update animais set peso  = 10.00 where id = 4
![Altere o peso do Garfield para 10 quilogramas;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/4fc08f4f-d839-433a-b119-125ea14bd748)
### Aqui fizemos a mudança do peso do animal

## 3- Crie um campo altura para os animais:
#### alter table add altura decimal (9,2)
![Crie um campo altura para os animais;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/2a0679af-3002-4eff-ac62-e612a820b859)
### Nesse caso foi incluido na tabela a coluna altura

## 4- Crie um campo observação para os animais:
#### alter table animais add observação varchar (200)
![Crie um campo observação para os animais;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/0ffb56a3-625f-4890-833d-c948fc1a7add)
### Aqui foi incluido a coluna observação para mostrar mais sobre os animais

## Remova todos os animais que pesam mais que 200 quilogramas:
#### delete from animais where peso > 50
![Remova todos os animais que pesam mais que 200 quilogramas](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/a1e4653a-9137-4abc-b365-98e8c801ad43)
### Aqui fizemos a exclusao de animais com um devido peso

## Remova todos os animais que o nome inicie com a letra ‘C’:
#### delet from where nome like '&C'
![Remova todos os animais que o nome inicie com a letra ‘C’](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/18947f7a-27b7-4691-afaa-d81ca11d54ad)
#### Assim como os animais com os pesos, aqui fizemos a esxlusao de animais que começavam com uma letra especifica

## Remova o campo cor dos animais:
#### alter table animais drop cor 
![Remova o campo cor dos animais;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/97ef3a05-561a-405b-a4b6-4edba043e425)
### Nesse caso fizemos a exclusao de uma coluna da tabela 

## Aumente o tamanho do campo nome dos animais para 80 caracteres:
#### alter table animais modify colunm nome varchar (80)
![Aumente o tamanho do campo nome dos animais para 80 caracteres;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/07ab667b-9b23-4b86-bd2b-5f464356711d)
### nesse caso fizemos a alteração da quantidade de caracteres da coluna nome da tabela animais 

## Remova todos os gatos e cachorros:
#### delete from aniamais drop especie like 'gato'
![Remova todos os gatos e cachorros](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/96858493-a3a4-4cfa-8a9e-a8b2f25a4253)
### Nesse caso fizemos a exlusao de todos gatos e cachorros, porem na tabela animais, não constava a especie cachorro cadastrada 

## Remova o campo data de nascimento dos animais:
#### alter table animais drop nasc
![Remova o campo data de nascimento dos animais](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/5b3105ff-352e-4420-895e-f41599bda495)
### Aqui fizemos a exclusao das datas de nascimento dos animais 

## Remova todos os animais:
#### alter table drop animais 
![Remova todos os animais](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/77870683-308b-4258-b6c3-7f81b4674f9b)
#### Nesse penultimo caso estamos finalizando a limpesa da tabela, sendo assim começamos a exclusao dos animais cadastrados

## Remova a tabela especies:
#### alter table animais drop especies 
![Remova a tabela especies](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/9d2f188d-bc6c-4553-9bb7-075e2ce5bd43)
### Para finalizar fizemos a exclusao da acoluna especie da tabela 

# Muito obrigado!

