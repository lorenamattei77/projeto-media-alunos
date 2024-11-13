# projeto-media-alunos

# main.py

def calcular_media(notas):
    return sum(notas) / len(notas)

def obter_notas():
    notas = []
    for i in range(1, 4):
        nota = float(input(f"Digite a nota {i}: "))
        notas.append(nota)
    return notas

def exibir_resultado(media):
    print(f"A média do aluno é: {media:.2f}")

if __name__ == "__main__":
    notas = obter_notas()
    media = calcular_media(notas)
    exibir_resultado(media)
