# Projeto Viva Sua Profissão

Template inicial da disciplina **Administração de Websites** (Curso Técnico em Desenvolvimento de Sistemas).

## Estrutura de Pastas

```text
├── index.html               # Página inicial do portal
├── css/
│   └── style.css            # Estilos globais e variáveis de cores
├── img/                     # Pasta para banner e imagens do grupo
└── pages/
    ├── habilidades.html     # Habilidades, formação e mercado
    ├── materiais.html       # Banner, proposta de e-book e esboço de landing page
    └── sobre.html           # Mapa do site e justificativa técnica
```

## Como publicar no GitHub Pages (Aula 2)

1. Crie um repositório público no GitHub (ex.: `viva-sua-profissao`).
2. Envie todos os arquivos mantendo exatamente esta estrutura de pastas.
3. No repositório, acesse **Settings > Pages**.
4. Em **Source**, selecione `Deploy from a branch`, escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
5. Aguarde cerca de 1 minuto e acesse o link gerado (`https://seu-usuario.github.io/viva-sua-profissao/`).

## Regras de Ouro para Não Quebrar o Site

- **Nunca** use barra `/` no início de links ou imagens (use `css/style.css` e não `/css/style.css`).
- Nomeie imagens e arquivos sempre em **letras minúsculas, sem espaços e sem acentos** (ex.: `banner-principal.png`).
