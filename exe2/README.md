# EXE2

![](imgs/exe2.gif)

A inspiração desse exercício veio do alarme de cinto de segurança do carro, quando o carro está ligado e andando o motorista possui um tempo para colocar o cinto, antes que o alarme começe a tocar.

No nossa caso, a indicação de que o carro está em movimento será feita pelo botão **vermelho**, ou seja, quando o botão vermelhor for pressionado devemos esperar 1s antes de soar o alarme (Led **amarelo**), o sensor do cinto será representado pelo botão **azul**. Quando ele for pressionado indica que o passageiro colocou o cinto e o alarme deve parar de soar.

- Usar 1 segundo de alarme entre apertar o botão vermelho e esperar o azul.

## Regras de implementação do firmware:

- Baremetal (sem RTOS).
- Utilizar timers
- Os leds devem parar de piscar apagados.
- Deve trabalhar com interrupções nos botões.  
- Não é permitido usar `sleep_ms(), sleep_us(), get_absolute_time()`.
- **printf** pode atrapalhar o tempo de simulação, comenta/remova antes de testar.

## Testes

O código deve passar em todos os testes para ser aceito:

- `embedded_check`
- `firmware_check`
- `wokwi`

Caso acredite que o seu código está funcionando, porém os testes estão falhando, preencha o forms:

[Google forms para revisão manual](https://docs.google.com/forms/d/e/1FAIpQLSdikhET4iqFwkOKmgD-G6Ri-2kCdhDLndlFWXdfdcuDfPnYHw/viewform?usp=dialog)
