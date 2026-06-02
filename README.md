# PyRent-a-car
Sistema de Gestão de Locação de Veículos

import os

resp = ''
while resp != '0':
    os.system('cls')
    
    print("##############################################")
    print("#######           PyRent-a-car         #######")
    print("######   Gestão de Locação de Veículos  ######")
    print("##############################################")
    print("######      1 - Módulo Clientes        #######")
    print("######      2 - Módulo Veículos         ######")
    print("######      3 - Módulo Locação          ######")
    print("######      4 - Módulo Sobre o Sistema  ######")
    print("#####       0 - Sair                   #######")
    print("##############################################")
    resp = input("##### Selecione a operação desejada: ")

    if resp == '1':   
        print()
        print("############################################")
        print("#####     Área do Cliente - PyRent     #####")
        print("############################################")
        print("#####                                  #####")
        print("#####          Funcionalidade          #####")
        print("#####         em desenvolvimento       #####")
        print("#####                                  #####")
        print("############################################")
        print()
        input("Tecle <ENTER> para continuar...")
        
    elif resp == '2':
        print()
        print("############################################")
        print("#####         Gestão da Frota           ####")
        print("############################################")
        print("#####                                  #####")
        print("#####          Funcionalidade          #####")
        print("#####         em desenvolvimento       #####")
        print("#####                                  #####")
        print("############################################")
        print()
        input("Tecle <ENTER> para continuar...")
        
    elif resp == '3':
        print()
        print("############################################")
        print("#####         Painel de Aluguel       ######")
        print("############################################")
        print("#####                                ######")
        print("#####          Funcionalidade          #####")
        print("#####         em desenvolvimento       #####")
        print("#####                                  #####")
        print("############################################")
        print()
        input("Tecle <ENTER> para continuar...")
        
    elif resp == '4':
        print()
        print("############################################")
        print("#####       Sobre o PyRent-a-car       #####")
        print("############################################")
        print("#####                                  #####")
        print("#####  PyRent-a-car: Um sistema de     #####")
        print("#####  Gestão para Locação de Veículos #####")
        print("#####                                  #####")
        print("#####  Desenvolvedor(a):               #####")
        print("#####  Najara Oliveira Bernardo        #####")
        print("#####                                  #####")
        print("#####  Ambiente de Desenvolvimento:    #####")
        print("#####  Visual Studio Code (VS Code)    #####")
        print("#####                                  #####")
        print("############################################")
        print()
        input("Tecle <ENTER> para continuar...")
        
    elif resp == '0':
        print()
        print("############################################")
        print("### Motor desligado. Até a próxima viagem! #")
        print("############################################")
        print()
        input("Tecle <ENTER> para continuar...")
        
    else:
        print()
        print("############################################")
        print("#####    Você digitou uma opção inválida ####")
        print("############################################")
        print("#####                                  #####")
        print("#####       Retorne ao menu principal  #####")
        print("#####       e digite uma rota válida   #####")
        print("#####                                  #####")
        print("############################################")
        print()
        input("Tecle <ENTER> para continuar...")

print("\n Motor desligado. Até a próxima viagem!")
