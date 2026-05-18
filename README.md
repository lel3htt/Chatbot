# Chatbot
# Mensagem de boas-vindas do robô
print("Olá! Eu sou o ChatBot. Qual é o seu nome?")

# O programa espera você digitar o nome e guarda na memória
nome_usuario = input()

print(f"Prazer em te conhecer, {nome_usuario}! Como posso te ajudar hoje?")
print("Digite o número da sua dúvida:")
print("1 - O que significa ADS?")
print("2 - Qual a melhor linguagem para começar?")
print("3 - Sair do chat")

# Este comando faz o chatbot rodar sem parar até você decidir sair
while True:
    # O programa espera você digitar uma opção
    opcao = input("Escolha uma opção (1, 2 ou 3): ")

    # Se você digitar 1
    if opcao == "1":
        print("ADS significa Análise e Desenvolvimento de Sistemas. É o seu curso!")
    
    # Se você digitar 2
    elif opcao == "2":
        print("Python! É a linguagem mais amigável para quem está começando do zero.")
    
    # Se você digitar 3
    elif opcao == "3":
        print(f"Até logo, {nome_usuario}! Bons estudos em ADS!")
        break  # Este comando encerra o chatbot
    
    # Se você digitar qualquer outra coisa
    else:
        print("Opção inválida. Digite apenas 1, 2 ou 3.")

    print("\nDeseja algo mais?")
