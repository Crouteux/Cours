# Cours

Des cours de NSI légèrement improvisés qui survolent des concepts intéressants en informatique

## Classes

Une classe représente les propriétés et fonctions qui définissent un objet, à la manière d'un schéma.

```py
class Human:
  def __init__(self, name: str, age: int):
    self.name = name
    self.age = age


jojo = Human('Joseph', 16)
print(jojo.name) # Joseph
```

Ici on a une classe qui représente un humain avec les propriétés `name`, `age`.

On peut prendre cela une étape plus loin en ajoutant des méthodes à notre classe:

```py
class Human:
  def __init__(self, name: str, age: int):
    ...
  
  
  def saluer(self, message: str):
    print(f'Bonjour, je suis {name} ! {message}')


wadil = Human('Wadil', 15)
wadil.saluer('Il fait beau !') # Bonjour, je suis Wadil ! Il fait beau ! 
```
