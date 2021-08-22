# exercicio_20

#transforming strings into capital letter, lowers, counting letters, and splitting into words

nome = str ( input ('Digite seu nome completo:  ')) .strip()
print ('analizando seu nome...')
print ('seu nome em letras maiusculas é {}' .format (nome.upper()))
print ('seu nome em letras minusculas é {}' .format (nome.lower()))
print ('seu nome tem ao todo {} letras' .format(len(nome) - nome.count (' ')))
separa = nome.split()
print ('seu primeiro nome é {} e ele tem {} letras' .format (separa[0], len(separa[0])))
