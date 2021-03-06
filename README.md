# GabsMedical
![Alt Text](https://github.com/Kayannsoarez/GabsMedical/blob/master/Pics/Diagram.png)


## Introdução
Usando o Microprocessador da STM32 ARM Cortex M iremos implementar um dispositivo monitor de Frequência Cardíaca.

A frequência cardíaca pode ser considerada como o número de batimentos do coração por minuto. Os batimentos ou pulsações do coração são responsáveis por bombear sangue oxigenado para todo o corpo, através dos vasos do sistema circulatório. Assim, quando praticamos um esporte, o sistema nervoso induz a um aumento da frequência de batimentos do coração. Porém, o aumento da frequência cardíaca pode ocorrer de forma prejudicial ao corpo, podendo muitas vezes sobrecarregar o coração e causar danos à saúde do indivíduo.

A manutenção desse valor dentro dos parâmetros esperados pode significar, a manutenção da saúde do indivíduo. Logo os dados de frequência cardíaca podem ser muito úteis para medir os níveis de stress, ansiedade, observação da frequência cardíaca durante a prática de atividades físicas e na medição da frequência cardíaca em indivíduos com hipertensão. Assim o Dispositivo vem a ser util para monitorar as medidas necessárias para assegurar o bem estar do indivíduo. 

## Funcionamento do Sensor:
O sensor de frequência cardíaca efetua a leitura dos batimentos do coração usando um sensor de ritmo cardíaco óptico com amplificador e circuito de cancelamento de ruído, obtendo leituras de impulso de confiança. E em seguida envia esses dados analógicos para o microcontrolador através de um único pino de sinal. O sensor possui apenas 3 pinos, esses pinos se resumem em: Sinal, VCC, GND.  Portanto, observa-se que o sensor estar enviando dados analógicos para o microcontrolador, logo, conecta-se no pino analógicos do microcontrolador. O sensor possui baixo consumo de energia (cerca de 4mA) e sua tensão de operação é de 3~5V.

## Dados:
![Alt Text](https://github.com/Kayannsoarez/GabsMedical/blob/master/Pics/BPM.png)

http://tiny.cc/thingspeak_BPM

## Ambiente 
* STM32CubeMX.
* Atollic TrueSTUDIO.
* Framework STM32Cube HAL (Hardware Abstraction Layer).
* Thingspeak.

## Lista de material
* STM32F103C8T6.
* ESP8266 - (ESP-01).  
* Sensor de Frequência Cardíaca.
* Led 5mm Vermelho.
* Resistor 220R.
* Protoboard.
* Fonte Ajustável Protoboard.
* Bateria 9v.
* Jumpers.


## Grupo
* Kayann Soares `@Kayannsoarez`
* Cristiane Felicio `@crisfelicio`
