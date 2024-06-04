#  FECAP - Fundação de Comércio Álvares Penteado

## Grupo: Projeto 5

### Integrantes:
- Lucas Oliveira Batista (lucas.aspect22@gmail.com)

### Professores Orientadores:
- Prof. Rodnil da Silva
- Prof. Jose Carlos Buesso Junior
- Prof. Victor Rosetti

<p align="center">
<img src="file:///C:/Users/24025815/AppData/Local/Temp/Rar$DIa13972.36786/3fcf6b1e-f0d9-4e78-b980-0cfc32b8e1d5_1_11zon.jpg" alt="Brigada Verde" border="0">

</p>


## Descrição:

Este projeto de detecção de gás é uma solução prática e eficaz para monitorar a presença de gases perigosos em diversos ambientes. Utilizando o sensor MQ-2 junto com um Arduino, buzzer e LED, o sistema fornece alertas sonoros e visuais que ajudam a prevenir acidentes causados por vazamentos de gás. Este sistema pode ser implementado em residências, indústrias e outros locais onde a detecção precoce de gases é crucial para a segurança.

### Matérias Utilizadas no Projeto:     
Sensores DHT11 E MQ-2
Buzzer
ESP8266
Arduino uno Rev3

### Estrutura de Página:

-Raiz<br>
<br>
|-> Documentos<br> 
    |-->Documentação projeto Brigada verde.pdf<br>
|-->imagens<br>
|-->src<br>
 |-->Backend<br>
 |-->Frontend<br>
    |--> dht11_blynkfuncionando<br>
    |--> Mq-2_buzzerON<br>
|readme.md<br>

### Instalação

Requisitos de Hardware:
Placa Arduino Uno Rev3
Módulo ESP8266
Sensor de Gás MQ-2
Sensor de Temperatura e Umidade DHT11
Buzzer
LED
Jumpers e cabos de conexão
Fonte de alimentação adequada

Passos de Instalação:

1. Montagem do Circuito:
Conecte o sensor de gás MQ-2 ao Arduino seguindo as instruções do datasheet.
Conecte o sensor de temperatura e umidade DHT11 ao Arduino conforme especificado no datasheet.
Conecte o buzzer e o LED ao Arduino, garantindo a polaridade correta.
Conecte o módulo ESP8266 ao Arduino usando jumpers.

2. Preparação do Ambiente:
Escolha o local de instalação do sistema de detecção de gás. Recomenda-se um local centralizado e bem ventilado.
Certifique-se de que haja uma fonte de alimentação próxima para alimentar o sistema.
Verifique se há uma conexão Wi-Fi disponível para o módulo ESP8266, caso o sistema utilize comunicação sem fio.

3. Configuração do Código:
Abra o código fonte fornecido para o Arduino e o ESP8266 em seus respectivos ambientes de desenvolvimento (Arduino IDE, por exemplo).
Certifique-se de que todas as bibliotecas necessárias estejam instaladas corretamente.
Personalize as configurações do código, como o nome e senha da rede Wi-Fi, se aplicável.
Compile e faça o upload do código para o Arduino e o ESP8266.

4. Teste do Sistema:
Ligue o sistema de detecção de gás, garantindo que todos os componentes estejam alimentados corretamente.
Observe o comportamento do LED e do buzzer em resposta à detecção de gases perigosos.
Realize testes adicionais conforme necessário para garantir o funcionamento adequado do sistema.
