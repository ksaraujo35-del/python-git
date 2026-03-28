# python-git
Claro! Aqui está o tutorial organizado em **uma única página**, de forma compacta e contínua 👇

---

# 🐍 Tutorial Completo: Listas em Python (em uma página)

Listas em Python são estruturas que permitem armazenar vários valores em uma única variável. Elas são criadas usando colchetes `[]` e podem conter diferentes tipos de dados.

```python
frutas = ["maçã", "banana", "laranja"]
misturada = [1, "texto", 3.14, True]
```

Cada elemento da lista possui um índice, começando em 0:

```python
print(frutas[0])   # maçã
print(frutas[1])   # banana
print(frutas[-1])  # laranja (último elemento)
```

Você pode alterar valores diretamente pelo índice:

```python
frutas[1] = "uva"
```

Para adicionar elementos, use:

```python
frutas.append("abacaxi")     # adiciona no final
frutas.insert(1, "kiwi")     # adiciona em posição específica
```

Para remover:

```python
frutas.remove("banana")  # remove pelo valor
frutas.pop()             # remove o último
frutas.pop(1)            # remove pelo índice
del frutas[0]            # deleta item específico
```

O tamanho da lista é obtido com:

```python
len(frutas)
```

Você pode percorrer a lista com `for`:

```python
for fruta in frutas:
    print(fruta)

for i in range(len(frutas)):
    print(frutas[i])
```

Para verificar se um item existe:

```python
if "maçã" in frutas:
    print("Está na lista!")
```

O fatiamento (slicing) permite acessar partes da lista:

```python
numeros = [0, 1, 2, 3, 4, 5]

print(numeros[1:4])  # [1, 2, 3]
print(numeros[:3])   # [0, 1, 2]
print(numeros[3:])   # [3, 4, 5]
```

Métodos úteis:

```python
numeros = [3, 1, 4, 1, 5]

numeros.sort()     # ordena
numeros.reverse()  # inverte
numeros.count(1)   # conta ocorrências
numeros.index(4)   # posição do valor
```

List comprehension (forma avançada e elegante):

```python
quadrados = [x**2 for x in range(5)]
pares = [x for x in range(10) if x % 2 == 0]
```

Cuidado ao copiar listas:

```python
lista1 = [1, 2, 3]
lista2 = lista1        # referência (mesma lista)
lista2.append(4)

lista2 = lista1.copy() # cópia independente
```

Exercício prático:

```python
numeros = []

for i in range(5):
    valor = int(input("Digite um número: "))
    numeros.append(valor)

print("Lista:", numeros)
print("Maior:", max(numeros))
print("Menor:", min(numeros))
```

---

## 🚀 Resumo

Listas são:

* Mutáveis (podem ser alteradas)
* Dinâmicas (crescem e diminuem)
* Muito usadas para armazenar coleções de dados

---

Se quiser, posso transformar isso em **PDF**, **slide** ou **folha de cola (cheat sheet)** pra estudo rápido 👍
