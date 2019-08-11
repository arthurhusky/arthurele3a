# Fechadura controlada por senha
Nesse projeto, utilizei a placa **Arduino Uno R3 com Cabo USB A/B.**

![esseaqui](https://user-images.githubusercontent.com/53986050/62834372-7d154780-bc21-11e9-9ab5-d3bb3b969550.png)
# Descrição
Trata-se de uma **fechadura acionada por senha, que será digitada em um teclado alfanumérico.** Para isso, utilizei um **micro servo motor** que irá simular a fechadura de uma porta e um **teclado matricial** para inserção da senha. O teclado que utilizei possui 16 teclas, onde 10 teclas são numerais, 4 literais e 2 de caracteres. As 16 teclas estão dispostas em 4 linhas por 4 colunas e o teclado possui um conector de 8 pinos para ligação.
# Funcionamento
O **servo motor** é um componente comum em projetos de robótica, pois com ele é possível controlar o giro e a posição eixo através dos comandos enviados pela plataforma microcontrolada. Como exemplo de utilização, podemos citar o controle de movimento de partes de um robô, projetos de aeromodelismo e automodelismo. O modelo de **servo motor** que utilizei para o desenvolvimento desta prática é o **Micro Servo Motor SG90.** O papel do **teclado de membrana** neste protótipo é ser o **meio de comunicação entre hardware e usuário**, onde a pessoa irá digitar a senha e esta informação será processada pelo Arduino para validar se a senha é a correta ou não. Caso a senha digitada seja a correta, o **Arduino irá enviar ao servo motor** o comando para executar a ação de destrancar a fechadura e abrir a porta. Caso contrário, a fechadura permanece trancada e a porta fechada.
# Lista de Materiais
* Arduino Uno R3 com Cabo USB A/B

![esseaqui](https://user-images.githubusercontent.com/53986050/62834467-548e4d00-bc23-11e9-9323-f2777575e915.png)

* Teclado Matricial do Tipo Membrana 4×4

![esseaqui2](https://user-images.githubusercontent.com/53986050/62834473-8e5f5380-bc23-11e9-9ab6-2f9152bb4746.png)

* Micro Servo Motor SG90

![esseaqui3](https://user-images.githubusercontent.com/53986050/62834484-c2d30f80-bc23-11e9-8267-7f4a3ca4dcba.png)

* LED Vermelho 5MM

![esseaqui4](https://user-images.githubusercontent.com/53986050/62834501-ff067000-bc23-11e9-9140-71a660918a5f.png)

* LED Verde 5MM

![esseaqui5](https://user-images.githubusercontent.com/53986050/62834509-2a895a80-bc24-11e9-800a-872289c01623.png)

* Resistor de 150R

![esseaqui6](https://user-images.githubusercontent.com/53986050/62834529-5b698f80-bc24-11e9-8df7-87cbb309a733.png)

* Protoboard

![esseaqui7](https://user-images.githubusercontent.com/53986050/62834543-86ec7a00-bc24-11e9-9275-cbecff036673.png)


* Cabo Jumper Macho-Macho

![esseaqui8](https://user-images.githubusercontent.com/53986050/62834551-a4214880-bc24-11e9-83d4-b4395d2acd12.png)
