# Temp-Sensor-Fan-with-regulator
Ler a temperatura da água com um sensor NTC 50k, mostrar no LCD1602 I2C e ligar a ventoinha por relé quando atingir a temperatura definida.  Também inclui:  ajuste por 4 botões  menu no LCD  guardar configurações na EEPROM  proteção se o sensor falhar.

Material principal

1x Arduino (Uno, Nano, etc.)
1x Sensor de temperatura da água NTC 50k
1x LCD1602 com I2C
1x Resistor 51k
1x Resistor 1k
1x 2N2222
1x Relé 12V
1x Díodo 1N4007
1x Conversor 12V → 5V
1x Placa de 4 botões

Funções do sistema:

ler temperatura do sensor

mostrar no LCD

ligar a ventoinha acima da temperatura definida

desligar abaixo da temperatura definida

permitir ajustar valores no menu

guardar os valores mesmo depois de desligar o carro

ligar a ventoinha automaticamente se o sensor falhar
