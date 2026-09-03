# 1. Mensagem de boas-vindas
print("=== CALCULADORA DE CONSUMO DE ENERGIA ===")

# 2. Pedir as informações para o usuário
nome_aparelho = input("Digite o nome do aparelho: ")
potencia = float(input("Digite a potência em Watts (W): "))
horas_dia = float(input("Digite quantas horas ele fica ligado por dia: "))

# 3. Fazer o cálculo do consumo no mês
consumo_mensal = (potencia * horas_dia * 30) / 1000

# Cálculo opcional do valor em dinheiro (R$ 0,75 por kWh)
custo_estimado = consumo_mensal * 0.75

# 4. Mostrar o resultado na tela
print("\n--- RESULTADO ---")
print(f"Aparelho: {nome_aparelho}")
print(f"Consumo estimado: {consumo_mensal:.2f} kWh/mês")
print(f"Custo estimado: R$ {custo_estimado:.2f} por mês")
# ⚡ Calculadora de Consumo Elétrico

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

Este projeto é uma calculadora simples em Python para estimar o consumo mensal de energia (em kWh) e o custo de um aparelho eletrodoméstico.

## 🧮 Fórmula Utilizada
`Consumo Mensal (kWh) = (Potência em Watts * Horas de uso por dia * 30) / 1000`

## 🚀 Como Executar
1. Instale o Python no seu computador.
2. Execute o arquivo `app.py` no terminal:
   ```bash
   python app.py
