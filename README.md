nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))
nota3 = float(input("Digite a terceira nota: "))


media_simples = (nota1 + nota2 + nota3) / 3


peso1, peso2, peso3 = 2, 2, 3
media_ponderada_1 = (nota1 * peso1 + nota2 * peso2 + nota3 * peso3) / (peso1 + peso2 + peso3)

peso1, peso2, peso3 = 1, 2, 2
media_ponderada_2 = (nota1 * peso1 + nota2 * peso2 + nota3 * peso3) / (peso1 + peso2 + peso3)

print(f"Média Aritmética Simples: {media_simples:.2f}")
print(f"Média Ponderada (2, 2, 3): {media_ponderada_1:.2f}")
print(f"Média Ponderada (1, 2, 2): {media_ponderada_2:.2f}")
