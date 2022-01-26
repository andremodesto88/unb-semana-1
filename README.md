# unb-semana-1
exercicios
minutos = int(input('quantos minutos: '))
segundos = int(input('quantos segundos: '))

result = minutos * 60 + segundos

print(f'A quantidade de segundos é: {result}')



km = float(input('quantos km: '))
milha = km/1.61


print(f'A quantidade de milhas é: {milha:.2f}')


km = int(input('Quantos km você correu: '))
minutos = int(input('Quantos minutos: '))
segundos = int(input('Quantos segundos: '))

totalseg = (minutos * 60) + segundos
hora = totalseg/3600
milha = km/1.61
vmedia = milha/hora

print(f'A velocidade média é: {vmedia}')
