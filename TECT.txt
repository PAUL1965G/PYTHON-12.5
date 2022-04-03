money = float(input("введите сумму, которую вы планируете положить под проценты:"))
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
a = per_cent.get('ТКБ')*money/100
b = per_cent.get('СКБ')*money/100
c = per_cent.get('ВТБ')*money/100
d = per_cent.get('СБЕР')*money/100
deposit = 5600,5900,4280,4000
print(list(map(int,deposit)))
i = sum(deposit)
print(i)