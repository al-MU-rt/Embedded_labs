Це поєднання лабораторних робіт 5 та 6, так як я використовую плату STM32F407VET6, а на ній немає ЦАП CS43L22, 
то я вирішив реалізувати барометр з використанням датчика BMP280, окрім тиску він також вимірює температуру повітря.
Дані з датчика передаються в stm32 через I2C, далі по протоколу UART вони передаються в esp32 який виводить їх в COM-port.
