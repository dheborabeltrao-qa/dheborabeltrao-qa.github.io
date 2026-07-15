# Portfólio de QA da Dhébora

Website responsivo de página única para apresentar projetos, casos de teste, competências e experiência voluntária.

## Abrir o website

Dê dois cliques em `index.html`. O website funciona localmente e não precisa de instalação.

## Atualizar conteúdo

Abra `index.html` num editor de texto e procure por `CONTEÚDO EDITÁVEL`. Todo o conteúdo principal está dentro do objeto `PORTFOLIO`:

- `name`, `role`, `intro` e `about`: apresentação profissional
- `projects`: projetos, ferramentas e casos em destaque
- `timeline`: experiência e formação
- `skills`: grupos de competências
- `contacts`: e-mail, LinkedIn e GitHub

Nos contactos, substitua `#` pelo endereço completo. Exemplo:

```js
{ label: "LinkedIn", url: "https://www.linkedin.com/in/seu-perfil" }
```

## Publicar gratuitamente

Uma opção simples é usar o GitHub Pages:

1. Criar um repositório no GitHub.
2. Enviar o arquivo `index.html`.
3. Abrir `Settings`, depois `Pages`.
4. Em `Build and deployment`, selecionar `Deploy from a branch`.
5. Selecionar a branch principal e a pasta `/root`.

O website foi desenvolvido sem bibliotecas externas, fontes remotas ou imagens. Isso facilita a manutenção e torna o carregamento rápido.
