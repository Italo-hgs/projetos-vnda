



<<<<<<< HEAD

=======
>>>>>>> ce33c1c58d289ccf1e9c88b29ed4c7df3eadf130
- ![Computer](../images/prints/computer.png)
  - ![Print](../images/prints/02-home.png)

# HOME

## BANNER PRINCIPAL

***Informações:***

| Dúvida                          | Instrução                                                               |
| ------------------------------- | ----------------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                                 |
| **Onde será exibido**           | Home - Banner principal abaixo do header, ocupa 100% da largura da tela |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/banner/editar?id=5)            |

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                              |
| ------------- | ------------------- | ------------------------------------------------------- |
| **Imagem**    | :large_blue_circle: | Dimensão sugerida 2280x1010 pixels                      |
| **Título**    | :black_circle:      | Alt da imagem                                           |
| **Subtítulo** | :large_blue_circle: | Texto do botão "pipe" posição do texto - opções disponíveis abaixo |
| **Descrição** | :large_blue_circle: | Colocar descrição do banner em markdown                 |
| **Externo?**  | :large_blue_circle: | Selecionar se o link do banner deve abrir em outra aba  |
| **URL**       | :large_blue_circle: | Link de direcionamento                                  |
| **Posição**   | :black_circle:      | `home-banner-principal` e `home-banner-principal-mobile` para mobile |
| **Cor**       | :black_circle:      | Cor do texto                                            |

Posições de texto possíveis para colocar no campo subtítulo:
```md
left-top
left-center
left-bottom

center-top
center-center
center-bottom

right-top
right-center
right-bottom

ex.: BUTTON | center-center
```

## ÍCONES HOME

***Informações:***

| Dúvida                          | Instrução                                                        |
| ------------------------------- | ---------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                          |
| **Onde será exibido**           | Banners com ícone e texto abaixo do fullbanner                   |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/banner/editar?id=30)    |

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                                                                                               |
| ------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Imagem**    | :large_blue_circle: | Dimensão recomendade de 200x200 pixels                                                                                   |
| **Título**    | :black_circle:      | Alt da imagem                                                                                                            |
| **Subtítulo** | :large_blue_circle: | Texto ao lado do ícone                                                                                                   |
| **Descrição** | :no_entry:          |
| **Externo?**  | :no_entry:          |                                                                                                                          |
| **URL**       | :no_entry:          |                                                                                                                          |
| **Posição**   | :black_circle:      | `home-icons`                                                                                                             |
| **Cor**       | :no_entry:          |                                                                                                                          |

## SLIDER DE PRODUTOS PRINCIPAL

***Informações:***

| Dúvida                          | Instrução                                                               |
| ------------------------------- | ----------------------------------------------------------------------- |
| **Onde cadastrar**              | Tags                                                                    |
| **Onde será exibido**           | Seção com slider de produtos                                            |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/tags/editar?id=home-produtos) |

***Informações sobre os campos***

| Campo         | Funcional?          | Orientação                                |
| ------------- | ------------------- | ----------------------------------------- |
| **Nome**      | :black_circle:      | Nome da tag                               |
| **Título**    | :large_blue_circle: | Título da sessão                          |
| **Subtítulo** | :large_blue_circle: | Texto do botão                            |
| **Descrição** | :no_entry:          |                                           |
| **Tipo**      | :large_blue_circle: | `home-produtos`                           |
| **Imagem**    | :no_entry:          |                                           |

**Observações**

Quantidade de carrosséis em sequência definidos pela quantidade de tags do tipo `home-produtos`

## BANNERS DE APOIO

***Informações:***

| Dúvida                          | Instrução                                                       |
| ------------------------------- | --------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                         |
| **Onde será exibido**           | Banners de apoio abaixo do carrossel de produtos            |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/banner/editar?id=35)   |

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                                           |
| ------------- | ------------------- | -------------------------------------------------------------------- |
| **Imagem**    | :large_blue_circle: | Dimensão sugerida 600x450 pixels                                     |
| **Título**    | :black_circle:      | Não exibido no front                                                 |
| **Subtítulo** | :large_blue_circle: | Título superior `\|` título principal `\|` texto do botão        |
| **Descrição** | :large_blue_circle:          | Subtítulo do banner                                                  |
| **Externo?**  | :large_blue_circle:          | Selecionar se o link do banner deve abrir em outra aba               |
| **URL**       | :large_blue_circle:          | Link de direcionamento                                               |
| **Posição**   | :black_circle:      | `home-banner-apoio`                                             |
| **Cor**       | :black_circle:      | Cor do título principal                                              |


## LISTAGEM DE PRODUTOS

***Informações:***

| Dúvida                          | Instrução                                                               |
| ------------------------------- | ----------------------------------------------------------------------- |
| **Onde cadastrar**              | Tags                                                                    |
| **Onde será exibido**           | Home - Seção abas de produtos
| **Cadastro exemplo em staging** | [Admin](https://template5.vnda.dev/admin/tags/editar?id=produtos-grid)  |

***Informações sobre os campos***

| Campo         | Funcional?          | Orientação                                |
| ------------- | ------------------- | ----------------------------------------- |
| **Nome**      | :black_circle:      | Nome da tag                               |
| **Título**    | :large_blue_circle: | Título da seção                          |
| **Subtítulo** | :no_entry:          |                                           |
| **Descrição** | :no_entry:          |                                           |
| **Tipo**      | :large_blue_circle: | `home-produtos-abas`                      |
| **Imagem**    | :no_entry:          |                                           |

**Obs:**
```
Para adicionar uma nova aba de produtos, basta adicionar uma tag com o tipo `home-produtos-abas`
```

## TÍTULO SEÇÃO CATEGORIAS

***Informações:***

| Dúvida                          | Instrução                                                        |
| ------------------------------- | ---------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                          |
| **Onde será exibido**           | Título da seção de categorias acima da seção Instagram |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/banner/editar?id=40)                                       |


***Orientações sobre os campos:***


| Campo         | Funcional?          | Orientação                                             |
| ------------- | ------------------- | ------------------------------------------------------ |
| **Imagem**    | :no_entry: | Não utilizado                     |
| **Título**    | :black_circle:      | Controle interno                                         |
| **Subtítulo** | :large_blue_circle: | Título da seção                                                        |
| **Descrição** | :no_entry: | Não utilizado              |
| **Externo?**  | :no_entry: | Não utilizado  |
| **URL**       | :no_entry: | Não utilizado                               |
| **Posição**   | :black_circle:      | `home-banner-categoria-titulo`                                |
| **Cor**       | :no_entry: | Não utilizado                   |

## SEÇÃO CATEGORIAS

***Informações:***

| Dúvida                          | Instrução                                                        |
| ------------------------------- | ---------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                          |
| **Onde será exibido**           | Seção de categorias acima da seção instagram |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/banner/editar?id=39)                                       |


***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                             |
| ------------- | ------------------- | ------------------------------------------------------ |
| **Imagem**    | :large_blue_circle: | Dimensão sugerida 250x250 pixels                       |
| **Título**    | :black_circle:      | Alt da imagem                                         |
| **Subtítulo** | :large_blue_circle: | Texto da categoria                                                        |
| **Descrição** | :no_entry: | Não utilizado              |
| **Externo?**  | :large_blue_circle: | Selecionar se o link do banner deve abrir em outra aba   |
| **URL**       | :large_blue_circle: | Link de direcionamento                               |
| **Posição**   | :black_circle:      | `home-banner-categoria`                                |
| **Cor**       | :no_entry: | Não utilizado                   |


## TÍTULO INSTAGRAM

***Informações:***

| Dúvida                          | Instrução                                                        |
| ------------------------------- | ---------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                          |
| **Onde será exibido**           | Título e subtítulo do instagram |
| **Cadastro exemplo em staging** | [Admin](https://template7.vnda.dev/admin/banner/editar?id=15)                                         |


***Orientações sobre os campos:***
| Campo         | Funcional?          | Orientação                                             |
| ------------- | ------------------- | ------------------------------------------------------ |
| **Imagem**    | :no_entry: | Não utilizado                    |
| **Título**    | :black_circle:      | Controle interno                                          |
| **Subtítulo** | :large_blue_circle:          | Título da seção                                                        |
| **Descrição** | :large_blue_circle: | `@` da loja               |
| **Externo?**  | :no_entry: | Não utilizado  |
| **URL**       | :no_entry: | Não utilizado                                   |
| **Posição**   | :black_circle:      | `home-instagram`                                |
| **Cor**       | :no_entry: | Não utilizado                   |
***
