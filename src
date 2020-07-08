cond = ""
number = 0
newNumber = 0
print("Bem-vindo ao conversor de unidades.")
print()
while(cond != "sair"):
    print("Digite a operação que você deseja fazer\n(1)Binário -> Decimal\n(2)Decimal -> Binário\n(3)Hexadecimal -> Decimal\n(4)Decimal -> Hexadecimal")
    operation = int(input())
    if (operation == 1):
        print("Muito bem, agora digite o número que você quer converter até 11111111, com 8 casas: ")
        number = str(input())
        if (len(number) != 8):
            print("Por favor, insira um número binário com 8 casas.")
            print()
            continue
        else:
            number1 = int(number[0])
            number2 = int(number[1])
            number3 = int(number[2])
            number4 = int(number[3])
            number5 = int(number[4])
            number6 = int(number[5])
            number7 = int(number[6])
            number8 = int(number[7])
            newNumber = number8*1 + number7*2 + number6*4 + number5*8 + number4*16 + number3*32 + number2*64 + number1*128
            print(f"{number} convertido para decimal é >>{newNumber}<<.")
    elif (operation == 2):
        print("Muito bem, agora digite o número que você quer converter até 255: ")
        number = int(input())
        if(number > 255):
            print("Por favor, digite um número até 255.")
            continue
        else:
            newNumber0 = number%2
            newNumber1 = number//2%2
            newNumber2 = number//4%2
            newNumber3 = number//8%2
            newNumber4 = number//16%2
            newNumber5 = number//32%2
            newNumber6 = number//64%2
            newNumber7 = number//128
            print(f"{number} convertido para binário é >>{newNumber7}{newNumber6}{newNumber5}{newNumber4}{newNumber3}{newNumber2}{newNumber1}{newNumber0}<<.")
    elif (operation == 3):
        print("Muito bem, digite o número que quer converter até FF, com 2 casas: ")
        number = str(input())
        if (len(number) != 2):
            print("Por favor, insira um número hexadecimal com 2 casas.")
            continue
        else:
            number1 = number[0]
            number2 = number[1]
            if(number1 == "A"):
                number1 = "10"
            elif(number1 == "B"):
                number1 = "11"
            elif(number1 == "C"):
                number1 = "12"
            elif(number1 == "D"):
                number1 = "13"
            elif(number1 == "E"):
                number1 ="14"
            elif(number1 == "F"):
                number1 = "15"
            if(number2 == "A"):
                number2 = "10"
            elif(number2 == "B"):
                number2 = "11"
            elif(number2 == "C"):
                number2 = "12"
            elif(number2 == "D"):
                number2 = "13"
            elif(number2 == "E"):
                number2 ="14"
            elif(number2 == "F"):
                number2 = "15"
            number1 = int(number1)
            number2 = int(number2)
            newNumber = number1*16 + number2
            print(f"{number} convertido para decimal é >>{newNumber}<<.") 
    elif (operation == 4):
            print("Digite o número que você quer converter até 255: ")
            number = int(input())
            if(number > 255):
                print("Por favor, digite um número até 255.")
                continue
            else:
                number1 = number//16
                number2 = number%16
                number1 = str(number1)
                number2 = str(number2)
                if(number1 == "10"):
                    number1 = "A"
                elif(number1 == "11"):
                    number1 = "B"
                elif(number1 == "12"):
                    number1 = "C"
                elif(number1 == "13"):
                    number1 = "D"
                elif(number1 == "14"):
                    number1 = "E"
                elif(number1 == "15"):
                    number1 = "F"
                if(number2 == "10"):
                    number2 = "A"
                elif(number2 == "11"):
                    number2 = "B"
                elif(number2 == "12"):
                    number2 = "C"
                elif(number2 == "13"):
                    number2 = "D"
                elif(number2 == "14"):
                    number2 = "E"
                elif(number2 == "15"):
                    number2 = "F"
                print(f"{number} convertido para hexadecimal é >>{number1}{number2}<<.")
    print("Se quiser encerrar a calculadora digite 'sair'")
    cond = str(input())
    print()
print("Obrigado por utilizar a calculadora.")