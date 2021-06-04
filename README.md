# Plugin QGIS 
## Vacinas-Covid-19

#### Grupo 4:
Carla Rodrigues, A84710  
Eduarda Ribeiro, A8541      

O presente trabalho prático consistiu na elaboração de um plugin para o QGIS, que permite visualizar a informação relativa à vacinação para a Covid-19 por ARS em Portugal Continental.  
A fonte de informação é: https://github.com/dssg-pt/covid19pt-data/blob/master/vacinas_detalhe.csv , que recorre aos relatórios semanais  de vacinação emitidos pela DGS.
A camada das ARS foi extraída do Geosaúde.


Quando o plugin é iniciado, é possível escolher a métrica a visualizar:  
![alt text](https://github.com/eduardalopesribeiro/Vacinas-Covid-19/blob/e06d5d322ce42bc3ad6750413b457510f29c9b15/Imagens/Dialog.jpg)

Assim, de acordo com a métrica selecionada, é criada uma camada com a informação requerida (doses ou percentagem de doses, data e ARS correspondente):  

![alt text](https://github.com/eduardalopesribeiro/Vacinas-Covid-19/blob/13bf4f2ee599f37f73a8de68afdf4d8590642c3e/Imagens/Camada.jpg)


Com a utilização deste plugin, é ainda possível visualizar a evolução da vacinação por ARS de Portugal Continental, recorrendo à ferramenta "Temporal Data".
Para isso, nas propriedadas da camada criada, na secção "Temporal", colocam-se as seguintes definições:  
![alt text](https://github.com/eduardalopesribeiro/Vacinas-Covid-19/blob/e06d5d322ce42bc3ad6750413b457510f29c9b15/Imagens/TemporalDataSetting.jpg)


Depois, é necessário ajustando o controlador para "full range" e semanas:
![alt text](https://github.com/eduardalopesribeiro/Vacinas-Covid-19/blob/d1e64c3277501fd602425f52a3159ff78e486ae5/Imagens/ControladorTemporal.jpg)


Desta forma, é possível criar uma animação com a evolução da percentagem de vacinação por ARS em Portugal Continental, como por exemplo, o gif seguinte que corresponde
à evolução da percentagem de primeiras doses administradas por ARS.

![alt text](https://github.com/eduardalopesribeiro/Vacinas-Covid-19/blob/d1e64c3277501fd602425f52a3159ff78e486ae5/Imagens/PercentagemPrimeiraDose.gif)
