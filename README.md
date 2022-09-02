Exercício
#https://arnaldojr.github.io/IoT/aulas/lab6/ 

Ferramentas utilizadas:
- Nod-Red
- IDE Arduino
- JSON

Biblioteca usada:
- MFRC522
- Arduino Json

Pequeno Sistema de Identificação em IOT.

1. No primeiro fluxo, o sistema consegue captar a "Tag Frid" e faz uma ligação com o arduino. Após isso, ele envia as informações no formato JSON para o node-red que após tranformar a informação que vem em JSON, ele manda um tópico usando o MQTT.

2. No segundo fluxo, o nod-red coloca o valor da TAG no dashboard.


