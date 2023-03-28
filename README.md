# Feminicídio no estado de  São Paulo

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Piternicolas/Feminicidio-em-Sao-Paulo/blob/main/license)

![fem2](https://user-images.githubusercontent.com/124289899/228062355-3df56ce6-b2bf-4ea8-a842-65e309324d98.jpg)

## O Brasil em geral é um país muito violento, em 2022 ocupava o 8° lugar no ranking mundial de países mais violentos do mundo, principalmente quando se trata de violência contra a mulher, que em 2021 ocupava o 5° lugar no ranking mundial. Infelizmente se tornou comum vermos notícias na TV e na internet, em qualquer horário do dia sobre violência e assasinato contra as mulheres, nessa artigo irei apresentar alguns números de casos de feminicídio no estado de São Paulo, que por incrível que pareça é o estado com a menor taxa de feminicídio no Brasil, porém vendo o estado com menos casos de feminicídio já podemos ter noção de como está no resto do país.
---
* ### DADOS: http://www.ssp.sp.gov.br/transparenciassp/Consulta.aspx
* ### Bibliografia no final do artigo.
* ### O dados foram trabalhos em um jupiter nootebook no google colab, anexado a este artigo. https://colab.research.google.com/drive/1S_B7CwPzsvW1z6y8ULo3salQNdmBSoWN#scrollTo=EdUpefpNuCu6
---
![4479812](https://user-images.githubusercontent.com/124289899/228097743-2bece360-48d8-4c90-8e43-9ac772194468.jpg)
## O que é a Lei do Feminicídio?
A Lei **nº 13.104/2015** torna o **feminicídio** um homicídio qualificado e o coloca na lista de **crimes hediondos**, com penas mais altas, de 12 a 30 anos.
É **considerado feminicídio** quando o assassinato envolve **violência doméstica** e **familiar**, **menosprezo** ou **discriminação à condição de mulher da vítima.**
A lei do feminicídio foi promulgada em **março de 2015** e é **muito importante** entender essa lei pois nessa DataFrame encontramos casos que vão de vítimas com apenas **1 ano** até **88 anos** de idade.

* Há 1.047 registros de casos.
* No DataFrame os registros começam em **12/04/2015** e vão até **29/12/2022**.

# Idades das vítimas
* O caso envolvendo a mulher mais nova é uma criança com apenas **1 ano** de idade, da cor **branca** assassinada dia **14/02/2022** no município de **Penápolis-SP** em sua **residência**.
* O caso envolvendo a mulher mais velha é uma senhora com **88 anos** de idade, **pensionista**, da cor **preta** assassinada dia **23/12/2019** na **capital de São Paulo** em sua **residência**.

## Porcentagem de casos por idades:
* **Entre 0 e 11 anos:** 15 assassinatos (**1,4%** dos registros)
* **Entre 12 e 17 anos:** 35 assassinatos (**3,3%** dos registros)
* **Entre 18 e 59 anos:** 934 assassinatos (**89,2%** dos registros)
* **Acima de 60 Anos:** 63 assassinatos (**6%** dos registros)
* A idade com mais casos é **31 anos** com **40 registros** (**3,8%** dos registros)

![hist idades](https://user-images.githubusercontent.com/124289899/228092850-14bb45b5-7b63-4e55-adff-5d51e2a7d7a1.png)

É possível notar que há uma concentração maior entre **20** e **45** anos de idade. Também é notável que há casos de **crianças** e **idosas** assassinadas mostrando independente da idade nenhuma mulher está segura.

---

# Cores das vítimas
No DataFrame há 4 tipos de cores registradas e 2 tipos que não identificam a cor.

![cor vit](https://user-images.githubusercontent.com/124289899/228094964-eed1fee0-2435-4e2d-aa32-a1d88d1eeaa4.png)

* **Branca:** 57,5% dos registros.
* **Parda:** 34,9% dos registros.
* **Preta:** 6,8% dos registros.
* **Amarela:** 0,4% dos registros.
* **Não identificado:** 0,4% dos registros.

* Mais da *metade* dos registros são referentes a mulher **branca**, seguido da mulher **parda** com pouco mais de *1/3* dos registros.

---

# Municípios com mais casos
* No DataFrame há registros em **264** municípios porém abaixo vou plotar apenas o 5 com mais casos.
![muni sp](https://user-images.githubusercontent.com/124289899/228096964-08a23401-6ec9-49a8-bc73-dd6f6797f117.png)
* **São Paulo (Capital):** 22% dos registros.
* **Campinas:** 4,8% dos registros.
* **Guarulhos:** 2,7% dos registros.
* **Osasco:** 2,1% dos registros.
* **Sorocaba:** 1,6% dos registros.
* Na **Capital** de **São Paulo** e as cidades a sua volta é onde se concentram os maiores números de casos de feminicídio, ou mais precisamente no **sudeste** do estado.
![image](https://user-images.githubusercontent.com/124289899/228226667-270e80e7-d80f-43b9-bb8b-8e525c519a52.png)

---

# Profissões das vítimas
* Na coluna referente a **profissão** das vítimas **45,5%** das entradas não estão especificadas então abaixo vou apresentar o gráfico das 5 profissões com mais registros de feminicídio. Há **108** tipos de profissões diferentes.

![prof vit](https://user-images.githubusercontent.com/124289899/228227679-bdcfe638-14b0-4584-8202-afd4266392a7.png)

* **Prendas domésticas:** 10,2% dos registros.
* **Estudante:** 6,8% dos registros.
* **Desempregada:** 2,1% dos registros.
* **Aposentada:** 2% dos registros.
* **Empregada doméstica:** 1,7% dos registros.
* Essas são as principais profissões que mais sofreram com o feminicídio em São Paulo.

---

# Locais dos crimes
* Nos registros das **descrições dos locais** há **19** tipos descrições diferentes, porém vou apresentar os 5 mais recorrentes
![loc fem](https://user-images.githubusercontent.com/124289899/228243303-0eb7d2db-8d0a-4e6f-a67b-847d469f3051.png)
* **Residência:** 66,6% dos registros.
* **Via pública:** 21,6% dos registros.
* **Comércio e serviços:** 2,1% dos registros.
* **Unidade rural:** 2% dos registros.
* **Área não ocupada:** 1,4% dos registros.
* Logo de cara percebemos o que já era esperado, mais de 60% dos registros são de vítimas que foram assassinadas dentro de suas próprias casas.

---

# Feminicídio apresentado por anos
* Como falado no começo do artigo, a **Lei do Feminicídio** começou a valer apenas em 2015. Veremos como abaixo os casos por ano.
---
![year fem](https://user-images.githubusercontent.com/124289899/228252276-56e76c9d-1fda-4c9f-a4f5-026a917b1b52.png)
* Logo de cara vemos que o ano de **2022** foi o ano com mais registros de feminicídio, **193 assassinatos**.
* Desde quando começou valer a lei os números só cresceram ao decorrer dos anos, tendo uma uma **queda** nos anos de **2020** e **2021** porém voltando a **subir** em **2022** e atingindo o número **máximo** de casos por ano.
---
![meses fem](https://user-images.githubusercontent.com/124289899/228252799-056810cd-1bf1-4958-b666-b77d13c11cb2.png)
---
* Desde que começo a valer a lei houveram no mínimo 2 registros de feminicídio por mês.
* **2015** teve **novembro** como o pior mês com **8 casos** e no ano tendo no mínimo **2 casos** por mês.
* **2016** teve **maio** como o pior mês com **8 casos** e no ano tendo no mínimo **3 casos** por mês. 
* **2017** teve **janeiro** como o pior mês com **18 casos** e no ano tendo no mínimo **5 casos** por mês.
* **2018** teve **maio** e **outubro** como os piores meses com **16 casos** e no ano todo mês tendo no mínimo **5 casos**.
* **2019** teve o pior mês de todos desde que começou a lei, em **dezembro** chegando a **27 casos** e tendo o mínimo de **5 casos** por mês durante o ano.
* **2020** teve **março** como o pior mês com **21 casos** e no ano tendo no mínimo **8 casos** por mês.
* **2021** teve **maio** como o pior mês com **26 casos** e no ano tendo no mínimo **6 casos** por mês.
* **2022** teve **outubro** como o pior mês com **22 casos** e no ano tendo no mínimo **9 casos** por mês.
