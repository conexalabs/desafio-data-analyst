# Dicionário de dados:

Campo | Descrição
----- | ---------
name | Nome
survival | Sobrevivência (0 = Não, 1 = Sim)
pclass | Classe de bilhete (1 = 1ª, 2 = 2ª, 3 = 3ª)
sex | Sexo
age | Idade em anos
sibsp | Possui irmãos/cônjuges a bordo do Titanic (0 = Não, 1 = Sim)
parch | Possui pais/filhos a bordo do Titanic (0 = Não, 1 = Sim)
ticket | Número do bilhete
fare | Tarifa de passageiro
cabin | Número da cabine
embarked | Embarcado em (C = Cherbourg, Q = Queenstown, S = Southampton)
___

## Complemento:

### **pclass**
> Um proxy para status socioeconômico (SES)
> * 1ª = Superior
> * 2º = Médio
> * 3º = Inferior

### **age**
> A idade é fracionária se for menor que 1. Se a idade for estimada, é na forma de xx.5

### **sibsp**
>Define as relações familiares desta forma:
> * irmão, irmã, meio-irmão, meia-irmã
> * Cônjuge = marido, esposa (amantes e noivos foram ignorados)

### **parch**
> Define as relações familiares desta forma:
> * Mãe, Pai
> * Criança = filha, filho, enteada, enteado
> * Algumas crianças viajavam apenas com a babá, portanto parch = 0 para elas.