1) 91

2) def verifica(numero):
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

3) 
	a) 9
	b) 128
	c) 49
	d) 100
	e) 13
	f) 22

4) Na primeira visita, ligarei o primeiro interruptor por alguns minutos, desliguei-o e ativarei o segundo interruptor antes de entrar na sala das lâmpadas. identificando qual interruptor controlava a lâmpada acesa e, através da temperatura, cada um dos interruptores que eram de cada lâmpada apagada. Na segunda visita, restava apenas verificar o interruptor restante.

5) string = "Hello World!"

print(string[::-1])
