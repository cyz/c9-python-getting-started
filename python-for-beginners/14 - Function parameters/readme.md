# Parâmetros de funções

As funções permitem pegar o código repetido e movê-lo para um módulo que pode ser chamado quando necessário. As funções são definidas com a palavra-chave `def` e devem ser declaradas antes que a função seja chamada no seu código. As funções podem aceitar um ou mais parâmetros e retornar valores.

- [Funções](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

```python
def function_name(parameter):
    # código para executar
    return value
```

É possível atribuir aos parâmetros um [default value](https://docs.python.org/3/tutorial/controlflow.html#default-argument-values), tornando-os opcionais quando a função é chamada.

```python
def function_name(parameter=default):
    # código para executar
    return value
```

Ao chamar uma função, você pode especificar os valores para os parâmetros usando posição ou [nomeação nomeada](https://docs.python.org/3/tutorial/controlflow.html#keyword-arguments)


```python
def function_name(parameter1, parameter2):
    # código para executar
    return value

# A notação posicional passa nos argumentos na mesma ordem em que os parâmetros são declarados
result = function_name(value1,value2)

# Notação nomeada
result = function_name(parameter1=value1, parameter2=value2)
```
