# A História do Android

Projeto feito durante o **Curso de HTML5 e CSS3** do professor [Gustavo Guanabara](https://gustavoguanabara.github.io/), do canal Curso em Vídeo.

O conteúdo é sobre a história do Bugdroid, o mascote do Android, e o objetivo era praticar estrutura semântica e estilização. Acabei indo além e fiz três versões visuais do mesmo conteúdo só pra testar coisas diferentes.

## Temas disponíveis

| Tema | Arquivo | Descrição |
|---|---|---|
| **Light Mode** | `index.html` | Paleta azul clara, tema padrão |
| **Dark Mode** | `dark-mode.html` | Tons de azul-marinho escuro |
| **Glassmorphism** | `glass.html` | Efeito de vidro fosco com `backdrop-filter` |

## Tecnologias usadas

- HTML5 semântico (`<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`)
- CSS3: variáveis (`--custom-properties`), `flexbox`, `position: sticky`, `@media` queries
- `<picture>` + `<source media="...">` para imagens responsivas
- Google Fonts (Lora + Open Sans)

## Estrutura de arquivos

```
/
├── index.html
├── dark-mode.html
├── glass.html
└── assets/
    ├── imagens/
    │   ├── dan-droids.png
    │   ├── dan-droids-pq.png
    │   ├── irina-blok.jpg
    │   ├── irina-blok-pq.jpg
    │   ├── bugdroid.png
    │   └── favicon.ico
    └── styles/
        ├── style.css
        ├── dark-mode.css
        └── glass.css
```

## Como rodar

Não tem dependência nenhuma. Só clonar e abrir no navegador.

```bash
git clone https://github.com/rafcsaint/a-historia-do-android.git
cd a-historia-do-android
# abra o index.html no navegador
```

---

Feito por [Rafael Santos](https://github.com/rafcsaint).