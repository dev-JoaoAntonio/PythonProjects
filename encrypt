letras = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v',
          'w', 'x', 'z']  #ALFABETO
criptoLetras = ['1', '2', '3', '4', '5', '6', '7', '8', '9', '0', '!', '@', '#', '$', '%', '&', '*', ')', ')', '-', '=',
                '°', '?', '.']  #ALF-CRIPTOGRAFIA


def crip(frase):
    global letras, criptoLetras
    novaFrase = ''  # TEXTO FINAL
    for letraAtual in frase:  # PARA CADA LETRA NA FRASE ESCRITA ORIGINAL
        if letraAtual in letras:  # CHECANDO SE TEM A LETRA DA FRASE NA LISTA DO ALFABETO
            letraAtual = criptoLetras[
                letras.index(letraAtual)]  # MUDANDO A LETRA PARA A CORRESPONDETE NA LISTA DE LETRAS MODIFICADAS
            novaFrase += letraAtual

    return novaFrase


def descrip(frase):
    global letras, criptoLetras
    novaFrase = ''  # TEXTO FINAL
    for letraAtual in frase:  
        if letraAtual in criptoLetras:  
            letraAtual = letras[
                criptoLetras.index(letraAtual)]
            novaFrase += letraAtual
    return novaFrase


print(crip(input('Digite a frase que deseja criptografar: ').lower().lstrip().rstrip()))
print(descrip(input('Digite a frase que deseja descriptografar: ').lstrip().rstrip()))
