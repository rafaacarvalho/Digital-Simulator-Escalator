# Simulador-Digital-Escada-Rolante
 
Desenvolvido por Rafael Carvalho

If you need support on Discord: R3TCH#4505
                          
In this project I had 18 out of 20                        
                          
-PT-                          
Trata-se de uma escada rolante com um sensor S1 no fundo e um sensor S2 no
topo. O sensor S1 e S2 permitem detetar a entrada e saídas de pessoas da escada respetivamente. O motor
permite o funcionamento da escada em sentido ascendente, sendo operado com 2 sinais atuadores M1 e M2.
M1 indica a ativação do motor (1/0) e M2 indica a velocidade para máxima ou metade (1/0).
O sistema de controlo deverá detetar a presença de pessoas na escada e sempre que se encontrem pessoas na
escada o motor que aciona a escada deverá funcionar à velocidade máxima e sempre que não existirem pessoas
na escada o motor deverá passar para metade.
Quando as escadas rolantes devem arrancar paradas e só iniciam a operação quando surgir alguém em S1.
Devido a restrições da potência de motorização da escada, esta só poderá suportar no máximo 5 pessoas em
simultâneo. Assim, sempre que o número de pessoas dentro da escada atingir o número 5 o sistema deverá
acender uma luz vermelha LV no fundo da escada para que as pessoas não continuem a entrar.
O circuito deverá apresentar num display de 7 segmentos o número de pessoas que se encontram na escada,
em tempo-real.
Acrescentar ao controlo do motor a seguinte condição: Quando se detetam zero pessoas (velocidade metade), e
ao fim de 10 segundos nesse estado, o motor desliga e a escada deve pararimediatamente.
Quando se deteta a entrada de uma 6ª pessoa, o motor entra em modo de bloqueio e pára imediatamente. A
retoma só acontece após a escada estar vazia. Neste estado pode assumir que ambos S1 e S2 contabilizam a saída
das pessoas.

-EN-

This is an escalator with a sensor S1 at the bottom and a sensor S2 at the top. The S1 and S2 sensors allow for the detection of people entering and exiting the escalator respectively. The motor allows for the operation of the escalator in an upward direction, and is operated with 2 actuator signals M1 and M2. M1 indicates activation of the motor (1/0) and M2 indicates maximum or half speed (1/0).
The control system should detect the presence of people on the escalator and whenever there are people on the escalator the motor should operate at maximum speed, and whenever there are no people on the escalator the motor should switch to half speed.
When the escalators are stopped, they should only start operating when someone is detected at S1.
Due to motor power limitations, the escalator can only support a maximum of 5 people at a time. So, whenever the number of people in the escalator reaches 5, the system should turn on a red light LV at the bottom of the escalator so that people do not continue to enter.
The circuit should display on a 7-segment display the number of people on the escalator in real-time.
In addition to controlling the motor, the following condition should be added: When zero people are detected (half speed), and after 10 seconds in this state, the motor turns off and the escalator stops immediately.
When the entry of a 6th person is detected, the motor enters a lock mode and stops immediately. The escalator can only be restarted once it is empty. In this state, it can be assumed that both S1 and S2 count the exit of people.
                   
# COUNTER
![image](https://user-images.githubusercontent.com/67297263/214902505-7e997fb3-6045-4e7d-ab44-4cf7e640a117.png)

# 7-SEGMENT DISPLAY
![image](https://user-images.githubusercontent.com/67297263/214902579-30241e6a-d98a-46cb-bf17-31d43f706599.png)

# TIMER 10 SECONDS
![image](https://user-images.githubusercontent.com/67297263/214903009-6679d200-0e70-495b-8b4d-da9e7199b795.png)
