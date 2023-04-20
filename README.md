# zabbix-csv-to-xml
Script para converter dados de um arquivo CSV em um arquivo XML
Este script em Python lê dados de um arquivo CSV e cria um arquivo XML correspondente. Os dados são organizados em elementos XML com tags pré-definidas.

Pré-requisitos
Python 3.x
Arquivo CSV contendo dados na ordem: host, name, template, group, ip, interface, inventory_mode

Como usar
Salve o arquivo CSV com os dados que deseja converter em um arquivo XML.
Modifique o caminho do arquivo CSV no script para o caminho do seu arquivo.
Execute o script.
O arquivo XML resultante será criado no mesmo diretório do script com o nome "hosts.xml".

Como funciona
O script usa a biblioteca csv do Python para ler os dados do arquivo CSV e a biblioteca xml.etree.ElementTree para criar os elementos XML correspondentes. Para cada linha do arquivo CSV, é criado um elemento XML com tags pré-definidas para cada campo. No final, é criado um arquivo XML a partir dos elementos XML criados.
