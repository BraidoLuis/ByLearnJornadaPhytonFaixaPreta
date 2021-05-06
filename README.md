# ByLearnJornadaPhytonFaixaPreta
Eu fiz um código pra descobrir se você faz parte da minha família ou não

Fiz esse código com o que aprendi até agora com a jornada python faixa preta da ByLearn

print('Será que você faz parte da família Braido?')

nome = 'Dayanne'
sobrenome = 'Braido'

if nome == 'Dayanne' or nome == 'Luís Felipe' or nome == 'Luís Fernando' or nome == 'Luís Miguel' or nome == 'Eliane':
  print('Você tem o nome igual alguém da minha família')
  if sobrenome == 'Braido':
    print('Calma aí,é vc msm??')
else:
  print('Parece que eu acabei confundindo você,me desculpe')
  
  
Esse é um código de calcular média de exemplo

nota1 = 9.3
nota2 = 8.3

def verificar_aprovacao():
    media = calcular_media([nota1, nota2])

    if media >= 6:
      print('O Aluno foi aprovado!')
    else:
      print('O Aluno foi reprovado!')

def calcular_media(notas):
    quantidade = len(notas)

    soma = 0
    for nota in notas:
        soma = soma + nota

        media = soma / quantidade

        return media

verificar_aprovacao()
  
  
