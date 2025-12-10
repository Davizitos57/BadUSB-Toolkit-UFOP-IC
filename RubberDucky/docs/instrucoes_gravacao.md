# Instalação e uso do ambiente para programar o Arduino Leonardo (ATmega32u4) como um Rubber Ducky 

## 1. Instalar Arduino IDE
Acesse o site oficial da IDE e instale a versão **Legacy IDE (1.8.19)** para poder realizar os testes:
- https://www.arduino.cc/en/software

## 2. Selecionar a placa na IDE
Diferente do Digispark, o Arduino Leonardo já vem instalado com a IDE, então para utilzá-lo basta apenas selecioná-lo, vá em:

- **Ferramentas -> Placa -> Arduino AVR Boards -> Arduino Leonardo**

**Observação:** Caso tenha dúvidas de qual versão ou dispositivo arduino você está utilizando, basta conectá-lo na porta do seu computador, **sempre garantindo que ele esteja vazio antes** e ir em:

- **Ferramentas -> Obter informações da porta**

## 3. Verifique a porta selecionada 
A porta selecionada deve ser a **/dev/ttyACM0**, caso ela não esteja seleciona, vá em:
- **Ferramentas -> Portas -> /dev/ttyACM0**

Agora você está pronto para programar seu ATmega32u4 via USB! :)

## 4. Gravando e executando script

Após escrever o código referente ao script desejado para executar no seu dispositivo e inserir o arduino na porta do seu computador, vá em:

- **Sketch -> Carregar** 

    ou

- **Aperte o botão com símbolo de seta apontada para a direita na IDE**

Você verá a mensagem:

- **Carregando**

Aguarde aparecer a mensagem:

- **Carregado**

Após isso o dispositivo reinicia e executa o programa.
