def validar_temperatura(valor):
    try:
        return float(valor)
    except ValueError:
        print("Valor inválido! Informe um número inteiro ou decimal.")
        return None

def calcular_media_variacao(temp_min, temp_max):
    media = (temp_min + temp_max) / 2
    variacao = abs(temp_max - temp_min)
    return media, variacao

def soma_digitos(numero):
    try:
        numero_int = int(numero)
        return sum(int(digito) for digito in str(abs(numero_int)))
    except ValueError:
        print("Valor inválido! Informe um número inteiro.")
        return None

# Entrada de dados
temp_min = validar_temperatura(input("Informe a temperatura mínima do dia: "))
temp_max = validar_temperatura(input("Informe a temperatura máxima do dia: "))

if temp_min is not None and temp_max is not None:
    media, variacao = calcular_media_variacao(temp_min, temp_max)
    print(f"Média das temperaturas: {media:.2f}°C")
    print(f"Variação das temperaturas: {variacao:.2f}°C")

# Soma dos dígitos
numero = input("Informe um número inteiro para calcular a soma dos dígitos: ")
soma = soma_digitos(numero)
if soma is not None:
    print(f"A soma dos dígitos do número {numero} é {soma}.")


    def validar_temperatura(valor):
    try:
        return float(valor)
    except ValueError:
        print("Valor inválido! Informe um número inteiro ou decimal.")
        return None

def calcular_media_variacao(temp_min, temp_max):
    media = (temp_min + temp_max) / 2
    variacao = abs(temp_max - temp_min)
    return media, variacao

def soma_digitos(numero):
    if not numero.isdigit():
        print("Valor inválido! Informe um número inteiro.")
        return None
    return sum(int(digito) for digito in numero)

# Entrada de dados
temp_min = validar_temperatura(input("Informe a temperatura mínima do dia: "))
temp_max = validar_temperatura(input("Informe a temperatura máxima do dia: "))

if temp_min is not None and temp_max is not None:
    media, variacao = calcular_media_variacao(temp_min, temp_max)
    print(f"Média das temperaturas: {media:.2f}°C")
    print(f"Variação das temperaturas: {variacao:.2f}°C")

# Soma dos dígitos
numero = input("Informe um número inteiro para calcular a soma dos dígitos: ")
soma = soma_digitos(numero)
if soma is not None:
    print(f"A soma dos dígitos do número {numero} é {soma}.")