# Projeto-Final-Objetos-Inteligentes-Conectados-

O projeto se trata de um dispositivo feito com NodeMCU para medir a temperatura e umidade do ambiente e transmitir esses resultados para uma página na Web .Sempre que a umidade ou temperatura tiverem maior do que o recomendado ,o Cooler Fan(pequeno ventilador) será ativado.

## Materiais e Métodos
**- NodeMCU ESP-32**: O NodeMCU-32S é uma plataforma de prototipagem baseada no 
ESP32 e que é comumente utilizada no desenvolvimento de projetos ioT. A placa já conta 
com conversor USB serial integrado e porta micro-USB para alimentação e programação.
O controlador do NodeMCU-32S em questão é o módulo ESP-WROOM-32. Além do 
ESP32, o ESP-WROOM-32 possui também um cristal de 40MHz, memória flash integrada 
de 4MB, antena embutida e blindagem EMI.

**- Sensor DHT11**: O sensor de temperatura e umidade DHT11 possui um sensor de 
temperatura e umidade complexo com uma saída de sinal digital calibrada. Usando a 
aquisição de sinal digital exclusiva técnica e tecnologia de detecção de temperatura e 
umidade, que garante alta confiabilidade e excelente estabilidade de longo prazo.

**- Protoboard**: Uma placa de ensaio ou matriz de contato (ou protoboard, 
ou breadboard em inglês) é uma placa com furos (ou orifícios) e conexões condutoras 
ultilizada para a montagem de protótipos e projetos em estado inicial.

**- Módulo Relé 3V 10A**: O Módulo Relé 3V 1 Canal é um módulo de acionamento que 
permite integração com um grande número de sistemas microcontroladores, dentre 
estes: Arduino, ESP32, ESP8266, Raspberry PI e outros.
Vale destacar que esse modelo é especialmente desenvolvido para microcontroladores que 
trabalham com tensão de sinal de 3.3V, dispensando a necessidade de uso de conversores de 
nível lógico.


**- Cabos Jumper**

**- Cooler Fan**

**- Resistor 10k Ohm**
## Protocolos e Módulos de comunicação

Dentre as plataformas IoT existentes, uma das mais populares e simples de se usar é a ThingSpeak, a qual inclusive possui possibilidade de uso gratuito. Simplificadamente, o ThingSpeak permite o envio de dados numéricos a partir dos mais diferentes dispositivos (incluindo o ESP8266), permitindo a visualização de tais dados na forma de gráficos ao longo do tempo. Dessa forma, o ThingSpeak é a plataformas ideal para acompanhamento de dados numéricos de forma histórica / ao longo do tempo.


