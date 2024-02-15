# Ultrasonic-Sensor-Arduino

Este projeto utiliza um sensor ultrassônico HC-SR04 para medir distâncias e exibir o resultado no monitor serial. O código segue os princípios SOLID de programação orientada a objetos, criando uma classe Sensor e uma classe Manager para encapsular a funcionalidade e as dependências do sensor.

A imagem mostra o projeto montado em uma protoboard, com o sensor ultrassônico fixado em uma base de papelão.

## Código

O código está organizado em três arquivos principais:

- Sensor.h: define a interface da classe Sensor, que representa o sensor ultrassônico e suas operações
- Sensor.cpp: implementa os métodos da classe Sensor, usando a biblioteca Ultrasonic.h para facilitar a comunicação com o sensor
- Manager.h: define a interface da classe Manager, que gerencia o sensor e o monitor serial
- Manager.cpp: implementa os métodos da classe Manager, usando a biblioteca Serial.h para enviar e receber dados pelo monitor serial
- Ultrasonic-Sensor-Arduino.ino: contém a função setup e a função loop do Arduino, que instanciam e usam os objetos das classes Sensor e Manager

## Imagens

![Esquemático do projeto](images/Aula_Pratica_11_schematics.jpg)

Esquema do projeto.

![Imagem do projeto](images/Aula_Pratica_11.png)

Imagem do projeto montado em uma protoboard.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.