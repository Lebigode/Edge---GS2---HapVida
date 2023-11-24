Italo de Souza - RM 551500


Descrição do Problema de Saúde Abordado:

Este projeto aborda a necessidade de monitoramento contínuo da temperatura em ambientes de saúde, como hospitais ou residências.
 O monitoramento preciso da temperatura é crucial para garantir ambientes seguros e confortáveis para pacientes, especialmente aqueles com 
condições sensíveis à temperatura.

Visão Geral da Solução Proposta:

Utilizamos o ESP32 em conjunto com o sensor de temperatura DS18B20 para monitorar a temperatura do ambiente em tempo real.
 Os dados são enviados via MQTT, um protocolo de mensagens leve para pequenos sensores e dispositivos móveis, permitindo o monitoramento
 remoto das condições ambientais.


Os arquivos contém:

- Vídeo explicativo da solução.
- O projeto Wokwi zipado.
- Código Fonte em txt.
-Arquvo json para o node-red.


Configuração e Execução da Aplicação Requisitos:

ESP32 Dev Board
Sensor de Temperatura DS18B20
Conexão Wi-Fi
Arduino IDE ou ambiente de desenvolvimento compatível

Instruções de Configuração:

Conecte o sensor DS18B20 ao ESP32.
Certifique-se de ter as bibliotecas OneWire, DallasTemperature e PubSubClient instaladas no seu ambiente de desenvolvimento.
Carregue o código fornecido no seu ESP32.
Execução:
Após carregar o código, o ESP32 começará a monitorar a temperatura e enviará os dados para o broker MQTT. Os dados podem ser visualizados 
em um cliente MQTT ou em uma interface Node-RED configurada para assinar o tópico MQTT. Usamos a interface node-red que foi mandado o arquivo json junto.


Você pode ver a simulação do projeto no Wokwi através do seguinte link: https://wokwi.com/projects/381976966332044289

Link do vídeo no youtube: https://www.youtube.com/watch?v=IWypo3yJry8

Link do repositório do git: https://github.com/Lebigode/Edge---GS2---HapVida
