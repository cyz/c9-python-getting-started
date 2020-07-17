# Pacotes e módulos

## Módulos

[Módulos](https://docs.python.org/3/tutorial/modules.html) permitem armazenar blocos de código reutilizáveis, como funções, em arquivos separados. Eles são referenciados usando a instrução `import`.

``` python
# módulo de importação como espaço para nome
import helpers
helpers.display('Não é um aviso')

# importar tudo para o namespace atual
from helpers import *
display('Não é um aviso')

# importar itens específicos para o namespace atual
from helpers import display
display('Não é um aviso')
```

## Pacotes

[Distribuição de pacotes](https://packaging.python.org/glossary/#term-distribution-package) são arquivos externos que contêm recursos como classes e funções. Quase todos os aplicativos que você cria usam um ou mais pacotes. As importações de pacotes seguem a mesma sintaxe que os módulos que você criou. O [Python Package index](https://pypi.org/) contém uma lista completa de pacotes que você pode instalar usando [pip](https://pip.pypa.io/en/stable/).

## Ambientes virtuais

[Ambientes virtuais](https://docs.python.org/3.7/tutorial/venv.html) permitem instalar pacotes em uma pasta isolada. Isso permite que você gerencie melhor as versões.

``` console

```
