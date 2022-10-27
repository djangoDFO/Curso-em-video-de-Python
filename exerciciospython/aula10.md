n1 = float(input('Digite a primeira nota do aluno: '))
n2 = float(input('Digite a segunda nota do aluno: '))
m = (n1 + n2) / 2
print('A Média de notas do Aluno é: {}'.format(m))
if m >= 6.0:
    print('Aluno está dentro da média, PARABÉNS!')
else:
    print('Aluno abaixo da média, PRECISA ESTUDAR MAIS!')    
