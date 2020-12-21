# Sistema identificador de água e açúcar em solução salina

## Índice
+ [Sobre](#sobre)
+ [Pré-requisitos](#pre_req)
+ [Esquemático e simulações](#sim)
+ [Placa de circuito impresso](#cir)

<h2 id="sobre">Sobre</h2>

O objetivo desse projeto é construir um sistema de detecção de sal ou açúcar em um recipiente com água, utilizando o método da voltametria cíclica.

<h2 id="comecando">Começando</h2>

Siga estas instruções para replicar o procedimento. Todos os códigos e arquivos de circuitos se localizam acima.

<h3 id='pre_req'>Pré-requisitos</h3>

Os principais pré-requisito são os softwares: LTspice, Proteus (v8.6), Arduino IDE e Visual Studio Code.

Para programar a ESP8266 no VS Code, torna-se necessário instalar uma extensão chamada "PlatformIO". Além disso, precisa-se adicionar algumas bibliotecas que não estão presentes nos softwares listados, possuindo um guia de instalação nos anexos do pdf.

<h2 id="obr">Conteúdo obrigatório</h2>

<h5 id='sim'>Esquemático e simulações</h5>

As simulações foram realizadas através dos softwares Proteus e LTspice, uma vez que houve falhas no controle do offset pelo Proteus. Assim, para uma melhor funcionalidade, simulou-se todas as partes separadamente. Os nomes dos arquivos são "Completo" e "Offset".

Os esquemáticos se encontram na seção "Resultados - Esquemático" e seus resultados em "Resultados - Simulação" do pdf.

O código do arduino (pwm) está na pasta "potentiostat_Arduino", e deve ser incluido no Proteus, como demonstrado no anexo. Já as bibliotecas, se encontram na pasta "Extra", as quais serão incluidas seguindo o protocólo constatado nos anexos.

<h6 id='cir'>Placa de circuito impresso</h6>

A vizualização 3D e ligações da placa de circuito impresso localizam-se na seção "Resultados - Placa de circuito impresso" do pdf.

