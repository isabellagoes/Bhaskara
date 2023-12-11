# Bhaskara

Programa que calcula as raízes de uma equação de segundo grau, utilizando o método de Bhaskara.

Uma equação do segundo grau é dada pela expressão abaixo:

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/23e70cfa003f402d108ec04d97983fb62f69536e)

Assim, devemos receber do usuário os valores de `a`, `b` e `c`, e aplicar a fórmula de Bhaskara:

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/00c22777378f9c594c71158fea8946f2495f2a28)

## Dicas:

- Precisamos validar se o valor de `a` não é zero, porque nesse caso a equação não é do segundo grau.
- Calculamos o discriminante Δ (_delta_):

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/1edcf6fef18bec26bcc7988626af5fa4cea3b0f8)

- Como a raiz quadrada de um número negativo não é um número real, precisamos validar se Δ não é negativo.

- Depois, é só calcular e exibir as duas raízes:

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/17d4468eb7385fa759d10bf1c36a7aaf02dc3985)

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/9d3cd187aefdeaf0b95243342c3eb9db9009d3b6)

### _Exemplo 1 (`a == 0`):_

```
-- Equação do segundo grau --
(a): 0
(b): 2
(c): 5

Não é uma equação de segundo grau!
```

### _Exemplo 2 (`Δ < 0`):_

```
-- Equação do segundo grau --
(a): 1
(b): 2
(c): 3

Como delta = -8,00, a equação não possui raízes reais!
```

### _Exemplo 3:_

```
-- Equação do segundo grau --
(a): 1
(b): 2
(c): -3

x1 = 1,00 e x2 = -3,00
```

## Download

Baixe o arquivo a seguir e o descompacte:

[🗃 Download do arquivo .zip](dist/Bhaskara.zip)

A seguir, execute-o com o comando:

```
dotnet ObrigadoDevCSharp.dll
```

Ou, se for de sua preferência, é possível executar o programa com duplo-clique em seu ícone, no caso de estar utilizando o Windows.