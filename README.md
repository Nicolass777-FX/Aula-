# Aula-#

# departamento

print("=== Sistema de Recomendação de Equipamentos de TI ===")
print("Departamentos disponíveis:")
print("1 - Desenvolvimento de Software")
print("2 - Marketing")
print("3 - Recursos Humanos")
print("4 - Pesquisa e Desenvolvimento (P&D)")

departamento = input("Digite o nome do departamento: ").strip().lower()

if departamento == "desenvolvimento de software":
    print("Recomendação: Laptops de alto desempenho (com processadores rápidos e bastante memória RAM).")
elif departamento == "marketing":
    print("Recomendação: Tablets, para facilitar apresentações e mobilidade.")
elif departamento == "recursos humanos":
    print("Recomendação: Computadores Desktop, pela estabilidade e custo-benefício.")
elif departamento == "pesquisa e desenvolvimento" or departamento == "p&d":
    print("Recomendação: Equipamentos de última geração, com hardware de ponta.")
else:
    print("Departamento não reconhecido. Verifique a digitação e tente novamente.")

Código Excelente :)
