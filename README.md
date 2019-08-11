# Fechadura controlada por senha
Nesse projeto, utilizei a placa **Arduino Uno R3 com Cabo USB A/B.**
![esseaqui](https://user-images.githubusercontent.com/53986050/62834372-7d154780-bc21-11e9-9ab5-d3bb3b969550.png)
# Descrição
Trata-se de uma **fechadura acionada por senha, que será digitada em um teclado alfanumérico.** Para isso, utilizei um **micro servo motor** que irá simular a fechadura de uma porta e um **teclado matricial** para inserção da senha. O teclado que utilizei possui 16 teclas, onde 10 teclas são numerais, 4 literais e 2 de caracteres. As 16 teclas estão dispostas em 4 linhas por 4 colunas e o teclado possui um conector de 8 pinos para ligação.
# Funcionamento
O **servo motor** é um componente comum em projetos de robótica, pois com ele é possível controlar o giro e a posição eixo através dos comandos enviados pela plataforma microcontrolada. Como exemplo de utilização, podemos citar o controle de movimento de partes de um robô, projetos de aeromodelismo e automodelismo. O modelo de **servo motor** que utilizei para o desenvolvimento desta prática é o **Micro Servo Motor SG90.** O papel do **teclado de membrana** neste protótipo é ser o **meio de comunicação entre hardware e usuário**, onde a pessoa irá digitar a senha e esta informação será processada pelo Arduino para validar se a senha é a correta ou não. Caso a senha digitada seja a correta, o **Arduino irá enviar ao servo motor** o comando para executar a ação de destrancar a fechadura e abrir a porta. Caso contrário, a fechadura permanece trancada e a porta fechada.
# Lista de Materiais
* Arduino Uno R3 com Cabo USB A/B
