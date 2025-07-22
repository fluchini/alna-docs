# Guia Geral Markdown

Toda a documentação é feita utilizando a ferramente MkDocs. Para mais detalhes sobre o MkDocs visite [mkdocs.org](https://mkdocs.org).

Para criar esta documentação utilizamos o **Markdown**. O Markdown é uma técnica mais simplificada e eficiente de fazer 
documentação, voltada geralmente para times técnico da Tecnologia da Informação. 

Para saber mais sobre o Markdown visite o site [Markdown Wikipedia](https://en.wikipedia.org/wiki/Markdown).

Além do guia rápido abaixo, também indicamos os seguintes guias para você consultar tudo o que você pode fazer com o 
Markdown.

* Guia de Referênca Geral: [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
* Ferramenta de Uso Online: [Stackedit.io](https://stackedit.io/app#)
* Guia de Referênca Material: [Material Guide](https://squidfunk.github.io/mkdocs-material/reference/)


## Textos

Criando textos com Markdown. Amostras de textos de [Lorem Ipsum](https://www.lipsum.com/).

``` md
# Lorem Ipsum
Lorem Ipsum is simply dummy text of the printing and typesetting industry.

## Lorem Ipsum
Lorem Ipsum is simply dummy text of the printing and typesetting industry.

### Lorem Ipsum
Lorem Ipsum is simply dummy text of the printing and typesetting industry.

#### Lorem Ipsum
Lorem Ipsum is simply dummy text of the printing and typesetting industry.
```


## Estilos

Criando estilos em **Negrito** e *Itálico*. 

``` md
### Negrito
Aqui temos um exemplo de um **texto em negrito**.

### Itálico
Já o tiálico pode ser feito *assim* ou _assim_.
```


## Lista\Tópicos

Listas podem ser criadas com enumeração arábica ou simplesmente na forma de tópicos.

=== "Por Tópicos"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

    ``` md
    ### Por Tópicos.
    
    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci
    ```

=== "Por Enumeração"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

    ``` md
    ### Por Enumeração.
    
    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci
    ```


## Citação

Exemplos de como criar citações. Como:

> Ninguém aprende a andar de **patins** só vendo um vídeo na internet.
> Você precisa praticar também.

``` md
### Exemplo de Citação

> Ninguém aprende a andar de **patins** só vendo um vídeo na internet.
> Você precisa praticar também.
```


## Links

Exemplos de como criar [links](https://www.markdownguide.org/basic-syntax/#links).

``` md
### Links Para Docs Internos

[Home](index.md)

### Links Para Sites Externos

[Wikipedia](https://en.wikipedia.org/)
```


## Tabelas

Exemplos de como criar tables.

|Alinhado à direita | Alinhado a Esquesda | Centralizado     | Icons                |         |
|------------------:|:--------------------|:----------------:|----------------------|---------|
|`GET`              | Fetch resource      | 10.00            | :material-check:     | Euros   |
|`PUT`              | Update resource     | 200.00           | :material-check-all: | Dolars  |
|`DELETE`           | Delete resource     | 3000.00          | :material-close:     | Reais   |

``` md
|Alinhado à direita | Alinhado a Esquesda | Centralizado     | Icons                |         |
|------------------:|:--------------------|:----------------:|----------------------|---------|
|`GET`              | Fetch resource      | 10.00            | :material-check:     | Euros   |
|`PUT`              | Update resource     | 200.00           | :material-check-all: | Dolars  |
|`DELETE`           | Delete resource     | 3000.00          | :material-close:     | Reais   |
```


## Exmpressões

Podemos criar expressões matemáticas utilizando o [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

Você pode encontrar mais informações sobre o  **LaTeX** [aqui](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).

``` md
The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$
```

## Imagem

Adicionando imagem.

``` md
![alt text](../../../assets/image.png "Azure Architecture Diagram")
```

![alt text](../../../assets/image.png "Azure Architecture Diagram")

