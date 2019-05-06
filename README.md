# repo2
secondreporistory
import random
def losuj(n,m):
    lista=[]
    for i in range(0,m):
        dodaj=random.randint(0,m)
        lista.append(dodaj)
    return lista
print("Ile liczb wylosować?")
liczby=int(input())
print("Zakres od 0 do")
odp=int(input())
print(losuj(liczby,odp))
