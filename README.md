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

Nommées IT

Fonctions callback (appelée automatiquement)
MAIN puis Réorganiser le code en .c et .h


#define CLI_BUFFER_LENGHT
//appui sur entrée = 13
if(uart2_data != 13)
{
	if(cli_it < CLI_BUFFER LENGHT)
	{
		HAL_UART_TRANSMIT(&huart2, &uart2_data, 1, HAL_MAX_DE)
		cli_buffer[cli_it] = uart_data;
		cli_it++;
	}
}


port (0 ou 1)
led (0 et 15)
valeur (0 ou 1)






1: temps d'échantillonage, le nombre de bits sur lequel on travaille, la fréquence.
