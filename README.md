# exerciciomatriz
matriz = [[11, 2, 4], 
          [4, 5, 6], 
          [10, 8, -12]]
 
numero_lista = len(matriz)
coluna_principal = 0 
for linha in range(numero_lista):
    for coluna in range(numero_lista): 
        if linha == coluna: 
            coluna_principal = coluna_principal + matriz[linha][coluna]
print(coluna_principal)
