# grbl_controller_arduino_nano


Desenvolvido por Raul Pessoa

  Este software tem como objetvo controlar uma fresadora CNC que usa o firmware GRBL
  O programa foi desenvolvido de forma independente e todos os direitos dele são reservados apenas ao autor.
  cópias, transferencias e módificações deste Código são permanentemente proibidas exceto em casos onde haja concentimento do autor.
  ´p
  Dentre as funcionalidade do Software estão:
    Envios de Gcodes ao GRBL via comunicação Serial
    Controle dos eixos da maquina atravez de um módulo joystck e um teclado matricial
    Monitorar os status de funcionamento do GRBL
    Monitorar os deslocamentos dos eixos da máquina
    Monitorar a velocidade do Spindle de corte da maquina
    Monitorar a temperatura os drivers de controle dos motores de passo da máquina
    Suporte ao controle de um sistema de refrigeração via a ar da parte eletrônica da máquina
    Suporte ao contrle do sistema de exaustao da máquina

  Hardware necessário:
    Arduino Nano
    Módulo Micro Sd
    Módulo Joystick
    Teclado Matricial integrado a um módulo i2c
    Display LCD com módulo i2c
    4 push buttons
    2 sensores de temperatura Lm35
    Módulo Sensor Infravermelho


  Pinos de Ligação do Módulo Micro Sd
    SD card attached to SPI bus as follows:
      MOSI - pin 11
      MISO - pin 12
      CLK - pin 13
      CS - pin 4 (for MKRZero SD: SDCARD_SS_PIN)

  Pinos de Ligação Display LCD I2c
   SCL - pin A5
   SDA - pin A4

  Pinos de Ligação Teclado Matricial I2c
   SCL - pin A5
   SDA - pin A4

  Pinos de Ligação Sensor LM35
   Out_pin_01 - A0
   Out_pin_02 - A1

  Pinos de Ligação Joystick
   Control_X - A2
   Control_Y - A3
   Bot_joy - 6

  Pinos de Ligação Sensor INfravermelho
   Out_pin - 2

  Pinos de Ligação Teclado Push-Buttons
   BotNext - 10
   BotBack - 9
   BotControl - 8
   BotSend - 7
