# programa_pontuacao_rodrigo.py

# Armazena os pontos de cada categoria
pontos = {
    "Relatório de Análise Financeira (DRE e Fluxo de Caixa)": 15,
    "Mapeamento de Processos Operacionais (BPMN)": 10,
    "Plano de Ação Estratégico (Metodologia 5W2H)": 5
}

# Rodrigo entregou um conteúdo de cada categoria
pontuacao_total = sum(pontos.values())

# Exibe o resultado
print("Pontuação de Rodrigo:")
print("-" * 40)

for categoria, ponto in pontos.items():
    print(f"{categoria}: {ponto} pontos")

print("-" * 40)
print(f"Pontuação total: {pontuacao_total} pontos")