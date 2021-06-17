# Computador-Simulado
Apresentação do projeto: https://youtu.be/jGM3xHx-hxw


- Adição:
    - 1001
- Encerrar fluxo:
    - 1000
- Copiar registrador:
    - 1011
- Copiar acumulador:
    - 1100
- Ler da memoria:
    - 1101
- Armazena na memoria de dados:
    - 1110

    ## Instruções ROM 1

1. 11010000 = D0 = Leia pos 0 da mem, adicione o valor ao reg0
2. 10110000 = B0 = Copie Ry para Rx
3. 11010101 = D5 = leia pos 1 da mem, adicione o valor ao reg1
4. 10010100 = 90 = Some Rx com Ry. referenciando reg1 à Ry
5. 11000000 = C0 = Copia Ra para Rx
6. 11100011 = E3 = Armazena Ra na pos 3 da mem
7. 10000000 = 80 = Encerra

## Instruções ROM 2

1. 11010000 = D0 = Leia pos 0 da mem, adicione o valor ao reg0
2. 10110000 = B0 = Copie Ry para Rx
3. 11010101 = D5 = Leia pos 1 da mem, adicione o valor ao reg1
4. 10010100 = 94 = Some Rx com Ry ref reg 1
5. 11000000 = C0 = Copia Ra para Rx
6. 11011010 = DA = Leia pos 2 da mem, adicione o valor ao reg2
7. 10011000 = 98 = Some Rx com Ry ref reg 2
8. 11000000 = C0 = Copia Ra para Rx
9. 11011111 = DF = Leia pos 3 da mem, adicione o valor ao reg3
10. 10011100 = 9C = Some Rx com Ry ref reg 3
11. 11100000 = E0 = Armazena Ra na pos 0 da mem
12. 10000000 = 80 = Encerra
