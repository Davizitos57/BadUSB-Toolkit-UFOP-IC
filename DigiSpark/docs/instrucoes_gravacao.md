# Instalação e uso do ambiente para programar o DigiSpark (ATTiny85)

## 1. Instalar Arduino IDE
Acesse o site oficial da IDE e instale a versão **Legacy IDE (1.8.19)** para poder realizar os testes:
- https://www.arduino.cc/en/software

    ### 1.1 Instalar os drivers do DigiSpark (se necessário)
    Caso você esteja utilizando o sistema operacional Windows será necessário que você instale o **DigiSpark USB Driver**:
    - https://github.com/digistump/DigistumpArduino/releases

Após instalar, conecte o DigiSpark **SOMENTE QUANDO A IDE PEDIR**

## 2. Adicionar o Board DigiSpark na Arduino IDE
1. Abra *Arquivo -> Preferências*.
2. Em "URLs Adicionais para gerenciadores de placas" adcione: 
    - https://raw.githubusercontent.com/ArminJo/DigistumpArduino/master/package_digistump_index.json
3. Abra *Ferramentas -> Placa -> Gerenciador de placas*.
4. Pesquise por **Digistump AVR Boards** e instale.

## 3. Selecionar a placa
Vá em: 
    - **Ferramentas -> Placa -> Digistump AVR Boards -> Digispark**

Agora você está pronto para programar seu ATTiny85 via USB! :)

## 4. Gravando e executando script

Após escrever o código referente ao script desejado para executar no seu dispositivo, vá em:

- **Sketch -> Carregar** 

    ou

- **Aperte o botão com símbolo de seta apontada para a direita na IDE**

Você verá a mensagem:

- **Plug in device now... (will timeout in 60 seconds)**

Somente após a aparição dessa mensagem conecte o seu Digispark na porta USB. 

Aguarde aparecer a mensagem:

- **Micronucleus done. Thank you!**

Após isso o dispositivo reinicia e executa o programa.