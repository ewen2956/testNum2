# testNum2

Cours/TD de systèmes numériques

Sur STM32CUBEIDE :
  Il faut toujours mettre son code entre un BEGIN et un END
  Respecter où mettre les includes
  HAL : Librairie/API --> Mais consomme beaucoup en terme de puissance de calculs
  CUBEMX : GUI de STM32
  #define : c'est une macro
  #ifndef : évite l'inclusion multiple
  void Error_Handler(void); : Prototype
  
Interruptions : 

UART-->NVIC-->CPU
GPIO-->NVIC-->CPU
I2C-->--NVIC-->CPU
SPI-->NVIC-->CPU

Fonctions callback (appelée automatiquement)
