Exercício
#https://arnaldojr.github.io/IoT/aulas/lab6/ 

Pequeno Sistema de Identificação em IOT.

1. No primeiro fluxo, o sistema consegue captar a "Tag Frid" e faz uma ligação com o arduino. Após isso, ele envia as informações no formato JSON para o node-red que após tranformar a informação que vem em JSON, ele manda um tópico usando o MQTT.

2. No segundo fluxo, o nod-red coloca o valor da TAG no dashboard.

Usei como ferramenta o node-red e o IDE Arduino. Como biblioteca, usei o MFRC522 e o Arduino Json
