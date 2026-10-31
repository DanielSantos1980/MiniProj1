# MiniProj1 — Currículo em SPA com Vue.js

**Unidade curricular:** Programação Web Avançada (MEIW) — Tarefa 2.2

## Objetivo

Criar um currículo digital que funcione numa **única página `index.html`**, recorrendo à framework **Vue.js 3**. A navegação é interna e não implica carregar novas páginas HTML.

## Requisitos implementados

- [x] SPA numa única página `index.html`.
- [x] Secção **Quem sou eu?**.
- [x] Secção **O que faço?**.
- [x] Secção **Hobbies**.
- [x] Navegação por ligações internas (`#quem-sou`, `#o-que-faco`, `#hobbies`).
- [x] Janela modal para contactos e configuração das redes sociais.
- [x] Rodapé com ícones LinkedIn, GitHub, Facebook e Instagram.
- [x] Componentes/conteúdos reativos gerados com Vue.js (`v-for`, `v-if`, interpolação, `@click`, `:class`).
- [x] Layout adaptável a telemóveis, tablets e computadores.
- [x] Wireframe com versão desktop e mobile em PDF.

## Estrutura de ficheiros

```text
MiniProj1/
├── index.html
├── wireframe.pdf
├── README.md
└── ligacao_repositorio.txt
```

## Como executar

1. Extrair os ficheiros do ZIP para uma pasta com o nome `MiniProj1`.
2. Abrir `index.html` num navegador com acesso à Internet. A biblioteca Vue é carregada através da CDN `unpkg`.
3. Em alternativa, executar um servidor HTTP local: `python -m http.server 8000` e aceder a `http://localhost:8000/`.
4. Testar a navegação interna, a janela modal e os ícones sociais.

**Nota:** O site é uma SPA em `index.html`, sem sistema de compilação, ideal para esta atividade inicial. O Vue necessita de ligação à Internet para ser carregado. Se a UC exigir funcionamento offline, é necessário guardar uma cópia local autorizada da biblioteca Vue e atualizar o caminho do `script`.

## Personalização antes de submeter

1. No `index.html`, encontrar o objeto `perfil` e confirmar os dados biográficos.
2. Rever as listas `areas`, `hobbies` e `competencias`. O texto de demonstração foi preparado para um percurso em informática; ajustar qualquer informação que não se aplique.
3. Na lista `redes`, substituir os campos vazios `url:''` pelos URL **verdadeiros** dos seus perfis. Enquanto não forem configurados, os ícones abrem uma janela explicativa e não encaminham para um perfil fictício.
4. O contacto não inclui e-mail nem telefone por omissão. Adicionar informação apenas se pretender divulgá-la publicamente.
5. Atualizar `ligacao_repositorio.txt` após publicar no GitHub.

## Criar repositório MiniProj1 no GitHub

### Opção A — via website

1. Entrar em https://github.com e criar um repositório com o nome **MiniProj1**.
2. Carregar `index.html`, `wireframe.pdf`, `README.md` e `ligacao_repositorio.txt`.
3. Copiar o URL do repositório (ex.: `https://github.com/UTILIZADOR/MiniProj1`).
4. Atualizar o ficheiro `ligacao_repositorio.txt` com o URL verdadeiro e carregar a versão revista no Git.

### Opção B — via Git (repositório remoto já criado, vazio)

```bash
cd MiniProj1
git init
git add .
git commit -m "Criar currículo SPA em Vue.js e wireframe"
git branch -M main
git remote add origin https://github.com/UTILIZADOR/MiniProj1.git
git push -u origin main
```

Substituir `UTILIZADOR` pelo nome da sua conta GitHub.

## Para a submissão na plataforma

Entregar o wireframe e os restantes ficheiros pedidos pelo docente, incluindo o ficheiro com o URL do repositório. A avaliação terá como base os ficheiros efetivamente publicados no Git.

## Fontes de apoio

- Vue.js — https://vuejs.org/guide/quick-start
- MDN — https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Getting_started/Your_first_website

