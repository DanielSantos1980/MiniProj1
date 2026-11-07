# MiniProj1 — Currículo digital numa Single Page Application (SPA)

**Unidade curricular:** Programação Web Avançada  
**Curso:** 1.º ano do Mestrado em Engenharia Informática e Tecnologia Web (MEIW)  
**Tarefa:** 2.2 — Primeiro desenvolvimento Web  
**Autor:** Daniel Santos *

## 1. Objetivo

Este mini projeto tem como objetivo construir um **currículo pessoal numa única página Web**, utilizando HTML, CSS, JavaScript e a framework **Vue.js 3**. O trabalho foi pensado para aplicar conhecimentos de base e conhecer os princípios de uma SPA, sem recorrer a ferramentas de compilação ou a uma arquitetura desnecessariamente complexa.

A página contém as secções obrigatórias:

- **Quem sou eu?** — apresentação e percurso académico;
- **O que faço?** — atividade profissional e interesses na área da informática;
- **Hobbies** — interesses pessoais fora do trabalho.

O rodapé apresenta ícones de redes sociais e existe uma janela modal para contacto.

## 2. Ficheiros

```text
MiniProj1/
├── index.html                   # Toda a SPA (HTML, CSS, Vue.js)
├── wireframe.pdf                # Protótipos desktop e mobile
├── memoria_descritiva.pdf       # Breve documentação do mini projeto
├── README.md                    # Objetivos e instruções
└── ligacao_repositorio.txt      # Link a completar depois de publicar no GitHub
```

## 3. Opções técnicas

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura semântica, cabeçalho, secções e rodapé |
| CSS3 | Estilos, grelhas e adaptação ao tamanho do ecrã |
| JavaScript | Eventos e funcionamento da página |
| Vue.js 3 | Dados reativos, listas, navegação e janela modal |

A biblioteca Vue é carregada pela CDN oficial apresentada na documentação do Vue. Assim, não é necessário instalar Node.js, Vite ou outras ferramentas para executar esta atividade inicial. **É necessária uma ligação à Internet para carregar o Vue.**

### Exemplos de recursos Vue.js usados

- `{{ ... }}` — apresenta dados pessoais e textos a partir de `data()`;
- `v-for` — apresenta as competências, atividades, hobbies e redes sociais;
- `v-if` — mostra e oculta a janela modal;
- `:class` — assinala a secção de navegação selecionada;
- `@click` — executa ações nos links e nos botões;
- `methods` — organiza ações como abrir/fechar a janela modal.

## 4. Wireframe

O ficheiro **wireframe.pdf** contém duas versões do protótipo, uma para computador e outra para telemóvel. Mostra a distribuição do cabeçalho, apresentação, três secções do currículo e rodapé. A navegação é efetuada através de ligações internas, sem criar páginas HTML adicionais.


## 5. Fontes de apoio

- Documentação Vue.js: <https://vuejs.org/guide/quick-start>
- MDN — Your first website: <https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Getting_started/Your_first_website>
- Documentação GitHub Pages: <https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site>


