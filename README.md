list = []
pair = []
odd = []
c = 1
while True:
    n = int(input('Enter a number: '))
    list.append(n)
    resp = str(input('Do you want to continue?[S/N]'))
    if resp in 'Nn':
        break
print(f'The list elements are {list}')
for n in list:
    if n % 2 == 0:
        pair.append(n)
    else:
        odd.append(n)
print(f'Odd numbers: {odd}')
print(f'Even numbers: {pair}')
