# MiniProj1 — Currículo digital numa Single Page Application (SPA)

**Unidade curricular:** Programação Web Avançada  
**Curso:** 1.º ano do Mestrado em Engenharia Informática e Tecnologia Web (MEIW)  
**Tarefa:** 2.2 — Primeiro desenvolvimento Web  
**Autor:** Daniel Santos *(confirmar antes da publicação)*

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

> O site funciona numa única página. Os ficheiros PDF e Markdown são apenas documentos de apoio, não páginas adicionais da aplicação.

## 3. Opções técnicas

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura semântica, cabeçalho, secções e rodapé |
| CSS3 | Estilos, grelhas e adaptação ao tamanho do ecrã |
| JavaScript | Eventos e funcionamento da página |
| Vue.js 3 | Dados reativos, listas, navegação e janela modal |

A biblioteca Vue é carregada pela CDN oficial apresentada na documentação do Vue. Assim, não é necessário instalar Node.js, Vite ou outras ferramentas para executar esta atividade inicial. **É necessária uma ligação à Internet para carregar o Vue.**

Uma **SPA** não é o mesmo que uma **PWA**: este projeto aborda o conceito de SPA e não pretende incluir Service Workers ou funcionamento offline, pois esses requisitos não são pedidos na Tarefa 2.2.

### Exemplos de recursos Vue.js usados

- `{{ ... }}` — apresenta dados pessoais e textos a partir de `data()`;
- `v-for` — apresenta as competências, atividades, hobbies e redes sociais;
- `v-if` — mostra e oculta a janela modal;
- `:class` — assinala a secção de navegação selecionada;
- `@click` — executa ações nos links e nos botões;
- `methods` — organiza ações como abrir/fechar a janela modal.

## 4. Wireframe

O ficheiro **wireframe.pdf** contém duas versões do protótipo, uma para computador e outra para telemóvel. Mostra a distribuição do cabeçalho, apresentação, três secções do currículo e rodapé. A navegação é efetuada através de ligações internas, sem criar páginas HTML adicionais.

## 5. Como abrir o projeto

**Opção simples:** abrir o ficheiro `index.html` no navegador com acesso à Internet.

**Opção recomendada:** na pasta `MiniProj1`, executar:

```bash
python -m http.server 8000
```

Depois aceder a `http://localhost:8000`.

## 6. Testes que devem ser efetuados

1. Confirmar que a página abre e mostra a apresentação pessoal.
2. Usar os links **Quem sou eu?**, **O que faço?** e **Hobbies** e verificar que se permanece no mesmo `index.html`.
3. Abrir e fechar a janela **Contacto**.
4. Verificar que os cartões das atividades e hobbies são apresentados a partir das listas Vue.
5. Testar a largura do navegador em computador e em telemóvel.
6. Verificar os ícones de redes sociais no rodapé.
7. Depois de publicar, abrir o URL do GitHub Pages e repetir os testes.

## 7. Personalização — antes de publicar

No final do ficheiro `index.html`, localizar a secção JavaScript `data()`. Aí é possível alterar:

- `perfil` — textos do currículo;
- `competencias` — conhecimentos apresentados;
- `areas` — atividades profissionais;
- `hobbies` — interesses pessoais;
- `redes` — endereços reais de redes sociais.

**Importante:** as redes sociais não possuem URLs pessoais por defeito, para não inventar endereços nem publicar dados privados. Enquanto não forem configuradas, os ícones abrem uma mensagem de aviso. Revê todos os textos e introduz apenas as informações que pretendes tornar públicas.

## 8. Como enviar para GitHub

1. Criar um repositório público chamado **MiniProj1** em <https://github.com/new>.
2. Usar **Add file → Upload files** e carregar os cinco ficheiros **dentro** da pasta `MiniProj1`.
3. Confirmar que `index.html` aparece na **raiz** do repositório.
4. Registar o commit com a mensagem `Tarefa 2.2 - Currículo digital SPA em Vue.js`.
5. Em **Settings → Pages**, selecionar **Deploy from a branch → main → /(root)** e guardar.
6. Preencher `ligacao_repositorio.txt` com o URL correto e carregar a versão atualizada para o GitHub.
7. Submeter na plataforma eLearning os ficheiros pedidos e o endereço do repositório.

**Exemplo de URL do repositório:** `https://github.com/UTILIZADOR/MiniProj1`  
**Exemplo de URL do site:** `https://UTILIZADOR.github.io/MiniProj1/`

Substituir `UTILIZADOR` pelo nome de utilizador real no GitHub.

## 9. Limitações conhecidas

- A interface não necessita de base de dados nem de servidor de aplicação.
- Não existe autenticação ou armazenamento permanente de dados, pois a tarefa pede apenas um currículo SPA.
- O Vue é carregado pela Internet; sem a biblioteca, os conteúdos dinâmicos não são apresentados.
- A janela de contacto é demonstrativa e não envia mensagens.

## 10. Fontes de apoio

- Documentação Vue.js: <https://vuejs.org/guide/quick-start>
- MDN — Your first website: <https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Getting_started/Your_first_website>
- Documentação GitHub Pages: <https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site>

**Contexto académico:** Mini projeto desenvolvido como exercício introdutório de programação Web com Vue.js no 1.º ano do MEIW.
