
## 1) Observe o trecho de código abaixo: 

Ao final do processamento, qual será o valor da variável SOMA? 

    int INDICE = 13, SOMA = 0, K = 0; 

 	enquanto K < INDICE faça 

	{ 

		K = K + 1; 

		SOMA = SOMA + K; 

	} 

 	imprimir(SOMA); 

SOMA = 91
#
## 2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência. 


    def verifica(numero):
        a, b = 0, 1

        while a <= numero:
            if a == numero:
                return True
            a, b = b, a + b

        return False

    num = 13

    if verifica(num):
        print(f"{num} pertence à sequência de Fibonacci.")
    else:
        print(f"{num} não pertence à sequência de Fibonacci.")

#
## 3) Descubra a lógica e complete o próximo elemento:  

    a) 9
	b) 128
	c) 49
	d) 100
	e) 13
	f) 22

#
## 4) Você está em uma sala com três interruptores, cada um conectado a uma lâmpada em uma sala diferente. Você não pode ver as lâmpadas da sala em que está, mas pode ligar e desligar os interruptores quantas vezes quiser. Seu objetivo é descobrir qual interruptor controla qual lâmpada. Como você faria para descobrir, usando apenas duas idas até uma das salas das lâmpadas, qual interruptor controla cada lâmpada?  

Na primeira visita, ligarei o primeiro interruptor por alguns minutos, desliguei-o e ativarei o segundo interruptor antes de entrar na sala das lâmpadas. identificando qual interruptor controlava a lâmpada acesa e, através da temperatura, cada um dos interruptores que eram de cada lâmpada apagada. Na segunda visita, restava apenas verificar o interruptor restante.

#
## 5) Escreva um programa que inverta os caracteres de um string. 

    string = "Hello World!"

    print(f'String invetida: {string[::-1]}')
