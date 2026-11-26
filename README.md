<p align="center"><img src="src/images/justice-league-movie-logo.png" width="420" alt="Justice League"></p>

# Justice League — página de filme (projeto de estudo)

Página de apresentação do filme *Liga da Justiça* inspirada no layout do Prime Video, feita para praticar **SASS (com mixins), Gulp e JavaScript**: banner principal, sinopse com ficha técnica, separadores com as personagens, trailer incorporado e rodapé, com layout responsivo.

> 🎓 **Projeto académico:** trabalho feito no curso para aprender a reproduzir um layout comercial real. Não tem fins comerciais nem qualquer ligação à Amazon, à Warner Bros. ou à DC; as marcas, logótipos e imagens pertencem aos respetivos donos.

🔗 **Demo (vê a página ao vivo):** [movie-justice-league.vercel.app](https://movie-justice-league.vercel.app)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Gulp](https://img.shields.io/badge/Gulp-CF4647?style=flat&logo=gulp&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

---

## ✨ O que pratiquei

**SASS**
- Estilos organizados em **parciais** por secção (`_hero`, `_sinopse`, `_characters`, `_trailer`, `_footer`)
- **Variáveis** num ficheiro próprio (`_variables.scss`)
- **Mixins** reutilizáveis para textos e títulos (`@mixin text`, `@mixin title`)
- Nomenclatura **BEM** (`characters__tabs__button--is-active`)
- **Media queries** em todas as secções para o layout responsivo

**JavaScript (sem bibliotecas)**
- **Separadores** para mostrar uma personagem de cada vez (`data-tab-button` / `data-tab-id`)

**Gulp (automatização)**
- Compilação e minificação do SASS
- Minificação do JavaScript com `uglify`
- Otimização de imagens com `imagemin`
- Tarefa `watch` para recompilar durante o desenvolvimento

## 📁 Estrutura

```
src/
├── images/    # Imagens originais
├── scripts/   # main.js
└── styles/    # main.scss e parciais por secção
gulpfile.js    # Tarefas de build (styles, scripts, images, watch)
index.html
```

## ▶️ Como executar

```bash
git clone https://github.com/hannasampaio/movie_justice-league.git
cd movie_justice-league
npm install
npm run build   # gera a pasta dist/
npm run dev     # recompila ao guardar
```

## 📚 Contexto

Projeto desenvolvido no âmbito da formação **Full Stack Java da EBAC** (módulos de SASS, Gulp e JavaScript), em 2023.

---

Desenvolvido por **Hanna Sampaio** · [LinkedIn](https://www.linkedin.com/in/hannasampaio7/) · [GitHub](https://github.com/hannasampaio)
