
print("=== CALCULADORA DE CONSUMO DE ENERGIA ===")


nome_aparelho = input("Digite o nome do aparelho: ")
potencia = float(input("Digite a potência em Watts (W): "))
horas_dia = float(input("Digite quantas horas ele fica ligado por dia: "))


consumo_mensal = (potencia * horas_dia * 30) / 1000


custo_estimado = consumo_mensal * 0.75


print("\n--- RESULTADO ---")
print(f"Aparelho: {nome_aparelho}")
print(f"Consumo estimado: {consumo_mensal:.2f} kWh/mês")
print(f"Custo estimado: R$ {custo_estimado:.2f} por mês")
# ⚡ Calculadora de Consumo Elétrico



`Consumo Mensal (kWh) = (Potência em Watts * Horas de uso por dia * 30) / 1000`


   python app.py
