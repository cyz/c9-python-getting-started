# Decorators

[Decorators](https://www.python.org/dev/peps/pep-0318/) são semelhantes aos atributos, pois adicionam significado ou funcionalidade aos blocos de código no Python. Eles são freqüentemente usados em estruturas como [Flask](http://flask.pocoo.org/) ou [Django](https://www.djangoproject.com/). A interação mais comum que você terá com os decoradores como desenvolvedor de Python é usando-os em vez de criá-los.

``` python
# Exemplo de Decorator
@log(True)
def sample_function():
    print('esta é uma função de amostra')
```
