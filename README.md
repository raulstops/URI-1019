# URI-1019
Codigo Python

n = int(input())
horas = (n // 3600)
minutos = (n % 3600) // 60
n = ((n % 3600) % 60)
print('{}:{}:{} ' .format(horas, minutos, n))
