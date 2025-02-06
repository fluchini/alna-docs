# Documentação Alna

O objetivo deste projeto é criar uma documentação técnica, de fácil acesso e edição para devs.

# Documentação MkDocs

Toda a documentação é feita utilizando a ferramente MkDocs. Para mais detalhes sobre o MkDocs visite [mkdocs.org](https://mkdocs.org).

## Passos Para Criar e Vizualizar a Documentação.

* Instale o MkDocs com o comando: `pip install mkdocs`
* Crie um projeto (caso ainda não exista) com o comando: `mkdocs new nome-do-projeto`.
* No diretório raiz do projeto, compile o projeto com o comando: `mkdocs build`.
* No diretório raiz do projeto, publique o projeto com o comando: `mkdocs serve`.
* Acesse a página `http://127.0.0.1:8000/`.

## Compilar e Publicar Documetação

* `mkdocs build` - Empacota a documentação no diretório `site` para publicação.
* `mkdocs serve` - Inicia o servidor de documentação com _live-loading_.
* `mkdocs help` - Imprime ajuda.

## Layout do Projeto

    mkdocs.yml    # Arquivo de configuração.
    docs/
        index.md  # Documento principal (home).
        ...       # Outras páginas markdown, imagens e outros arquivos.

## Material Para MkDocs

O tema **Material** é um estilo de cores e fontes para o MkDocs. Para mais informações acesse o site [mkdocs-material](https://squidfunk.github.io/mkdocs-material/).

Documentação completa para iniciar: [Começando](https://squidfunk.github.io/mkdocs-material/getting-started/)

Vídeo com o passo-a-passo: [Material para MkDocs com James Willett](https://www.youtube.com/watch?v=xlABhbnNrfI&ab_channel=JamesWillett).

Guia de referência: [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/reference/).

### Adicionar Tema Material

Para adicionar o tema **Material** use o seguinte comando: `pip install mkdocs-material`.

Agora, no arquivo mkdocs.yml adicione o atributo `theme`, conforme exemplo abaixo:

```YML
    site_name: Alna
    
    theme:
      name: material
    
    nav:
      - Início: index.md
      - Menu-01: 'menu-01/tools-and-configs.md'
      - Menu-02:
        - 'Submenu-02-1': 'menu-02/calendar.md'
        - 'Submenu-02-1': 'menu-02/course.md'
        - 'Submenu-02-1': 'menu-02/enrollment.md'
```
