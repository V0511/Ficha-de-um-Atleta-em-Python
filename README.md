# Ficha-de-um-Atleta-em-Python
Este repositório é para iniciantes que consegue tem uma fácil leitura de código. 

# Entrada  de dados.
-Nome, idade, peso, altura, números de campeonatos participados.

#INICIO DA FICHA

nome = str(input('Digite o nome do atleta: '))
idade = int(input('Digite a idade do atleta: '))
sexo = str(input('Digite o sexo do atleta: '))
modalidade = str(input('Digite sua modalidade: '))
peso = int(input('Digite peso do atleta:'))
altura = float(input('Digite a altura do aleta:'))
nascimento = str(input('Digite o ano de nascimento do atleta: '))
n = (idade - 2020)

print('Confirmando dados iniciais {}, {}, {}, {}, {}kg, {}m, {}-SP .'.format(nome,idade,sexo, modalidade, peso, nascimento, n))

#PAGAMENTO

valor = float(input('O valor é!R$ '))
pagamento = valor + (valor * 5 / 10)
print('Pagamento executado!')
print('Você pagou R${}, pois teve 5% de desconto. Seu valor original era de: {}.'.format(pagamento, valor))
