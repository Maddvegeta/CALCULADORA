algoritmo "Calculadora"
// Função : Calcular numeros reais
// Autor : Maddvegeta
// Data : 14/05/2024

var

Multiplicacao: real
Divisao: real
Valor1, Valor2: real
Soma:real
Subtracao: real


inicio
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
escreval("                          #*# Vamos calcular ! #*#                               ")

escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
                                    escreval("         #####   Subtracao #####               ")

escreval("")
escreval("")
escreval("Escreva o valor 1 para SUBTRAIR")
leia(Valor1)
escreval("Escreva o valor 2 para SUBTRAIR")
leia(Valor2)
escreval("")
escreval("")

            Subtracao <- Valor1 - Valor2

                      se Subtracao < 0 entao
            escreval("O numero é negativo.")
                        senao
            escreval ("O numero é positivo.")
                     fimse
            escreval("Sua Subtracao é : ", Subtracao)
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
                                    escreval("           #####   Soma  ######                ")
escreval("")
escreval("")
escreval("Escreva o valor 1 para SOMAR")
leia(Valor1)
escreval("Escreva o valor 2 para SOMAR")
leia(Valor2)
escreval("")
escreval("")

            soma <- Valor1 + Valor2

                 se soma < 0 entao
            escreval("O numero é negativo.")
                        senao
            escreval("O numero é positivo.")
                        fimse
            escreval("Sua soma é : ", soma)
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
                                    escreval("                   #####   Divisao   #####       ")
escreval("")
escreval("")
escreval("Escreva o valor 1 para DIVIDIR")
leia(Valor1)
escreval("Escreva o valor 2 para DIVIDIR")
leia(Valor2)

            Divisao <- Valor1 / Valor2

                    se Divisao < 0 entao
            escreval("O numero é negativo.")
                        senao
            escreval(("O numero é positivo.")
                         fimse
            escreval("Sua divisão é : ", Divisao)
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
escreval("")
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
                                      escreval("                         #####   Multiplicacao   #####      ")
escreval("")
escreval("")
escreval("Escreva o valor 1 para MULTIPLICAR")
leia(Valor1)
escreval("Escreva o valor 2 para MULTIPLICAR")
leia(Valor2)

            Multiplicacao <- Valor1 * Valor2

                          se Multiplicacao < 0 entao
            escreval("O numero é negativo.")
                        senao
            escreval("O numero é positivo")
                        fimse
            escreval("Sua Multiplicacao é : ", Multiplicacao)
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
fimalgoritmo

