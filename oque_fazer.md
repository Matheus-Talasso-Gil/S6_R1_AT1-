# Atividade sobre imagens em HTML

## Apropriação

### Código 1

```html
<img src="logo.png">
```

**Qual atributo está faltando?**

Falta o `alt`, que serve para descrever a imagem.

### Código 2

```html
<img src="logo.png" alt="Logotipo da empresa">
```

**Atende às boas práticas?**

Sim, porque tem texto alternativo. Para deixar a descrição mais clara,
podemos colocar o nome da empresa, como em `alt="Logotipo do SENAI"`.

## Aplicação

A proposta é criar uma página institucional. Usei o SENAI como tema no
arquivo `atividade_de_aplicacao.html`.

A página deve ter:

- Nome e descrição da instituição.
- Logotipo e foto ilustrativa.
- Texto alternativo adequado em cada imagem.
- Imagens organizadas na pasta `imagens`.

## Desafio profissional

O catálogo está em `desafio_profissional.html` e apresenta estas seções:

- Quem Somos: uma breve apresentação do SENAI.
- Serviços: desenvolvimento de sistemas, eletricista e formação profissional.
- Contato: um link para o site oficial do SENAI.

Foram usados três arquivos de imagem: o logotipo e duas fotos dos cursos.
Todas as imagens possuem `alt` e usam caminhos relativos, como
`imagens/desenvolvimento.jpg`.

Um caminho relativo indica onde o arquivo está a partir da página HTML.
Por isso, a pasta `imagens` deve acompanhar as páginas ao copiar o projeto.

## Arquivos do projeto

```text
S6_R1_AT1/
├── atividade_de_apropriacao.html
├── atividade_de_aplicacao.html
├── desafio_profissional.html
├── oque_fazer.md
└── imagens/
    ├── senai.svg
    ├── desenvolvimento.jpg
    └── eletricista.jpg
```

Cada atividade tem seu próprio HTML e usa a mesma pasta de imagens.
Os nomes dos arquivos estão em letras minúsculas, sem espaços ou acentos.

## Checklist

| Critério                                  | Sim | Não |
| ----------------------------------------- | :-: | :-: |
| Inseriu imagens corretamente              | ☑   | ☐   |
| Utilizou caminhos relativos               | ☑   | ☐   |
| Aplicou atributo `alt`                    | ☑   | ☐   |
| Organizou as imagens em pastas            | ☑   | ☐   |
| Utilizou nomenclatura adequada            | ☑   | ☐   |
| Demonstrou preocupação com acessibilidade | ☑   | ☐   |

## Revisão por um colega

- As imagens carregam no navegador?
- Os textos alternativos descrevem o que aparece nas imagens?
- Os nomes dos arquivos são claros?
- As páginas e a pasta de imagens estão organizadas?

## Autoavaliação

**Dá para entender a página sem ver as imagens?**

Os títulos e os parágrafos explicam a instituição e os serviços. O `alt`
oferece uma descrição da imagem quando ela não carrega ou quando alguém usa
um leitor de tela. Por isso, a descrição precisa combinar com a imagem.
