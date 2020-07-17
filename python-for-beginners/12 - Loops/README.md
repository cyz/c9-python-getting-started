# Laços de Repetição

## Laço de repetição For

Um laço de repetição [For](https://docs.python.org/3/reference/compound_stmts.html#the-for-statement) pega cada item em uma matriz ou coleção em ordem e o atribui à variável que você define.

``` python
names = ['Christopher', 'Susan']
for name in names:
    print(name)
```

## Laço de repetição While

Um laço de repetição [While](https://docs.python.org/3/reference/compound_stmts.html#the-while-statement) execute uma operação desde que uma condição seja verdadeira.

``` python
names = ['Christopher', 'Susan']
index = 0
while index < len(names):
    name = names[index]
    print(name)
    index = index + 1
```
