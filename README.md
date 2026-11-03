# Atividade da Aula 09 — HTML e CSS externo

Disciplina: Desenvolvimento Front-End para Web  
Professor: Israel Cunha

## O que foi feito

Esta é uma **nova versão da atividade da Aula 08** (repositório original: https://github.com/LuizBraga321/Atividade-de-CSS-interno), adaptada aos conceitos trabalhados na Aula 09.

O enunciado da página 48 da aula diz: **"Implemente telas utilizando os conceitos visto hoje em sala de aula com html e css."**

O trabalho mantém cinco páginas com seus assuntos originais e troca a apresentação anterior por um layout atualizado, com exemplos práticos:

- **CSS externo**: todas as cinco páginas usam o mesmo `style.css`, vinculado por `<link>` no `<head>`.
- **Seletor de tag**: `body`, `p`, `h1`, `a`, `table` etc. no CSS.
- **Seletor de classe (`.class`)**: `.cartao`, `.hero`, `.botao`, `.bloco-codigo` etc., reutilizáveis entre páginas.
- **Seletor de ID (`#id`)**: `#conteudo` e `#menu-principal` têm regras CSS próprias e ocorrem uma vez por página.
- **Agrupamento de seletores**: `h1, h2, h3` compartilham uma regra.
- **Background, margin e padding**: fundos, bordas, espaçamentos internos e externos aplicados a cards, menu, cabeçalho e hero.
- **Flexbox**: organiza menu, conteúdo, cartões e botões.
- **Responsividade**: `@media` reorganiza o layout em tablet e celular.
- **Tipografia**: propriedades como `font-family`, `font-size`, `font-weight`, `font-style`, `letter-spacing` e `line-height`.

## Arquivos

- `index.html` — página inicial / apresentação da atividade;
- `html.html` — estrutura e semântica do HTML;
- `css.html` — CSS externo, seletores de tag, classe e ID;
- `div.html` — DIV, Flexbox, margin, padding e responsividade;
- `textos.html` — estilização de textos;
- `style.css` — **único arquivo CSS** usado em todas as páginas.

## Como executar

1. Extraia o arquivo ZIP.
2. Abra a pasta no Visual Studio Code.
3. Abra `index.html` no navegador (ou use a extensão Live Server).
4. Navegue pelo menu para verificar todas as páginas.
5. Diminua a largura da janela para testar o layout responsivo.

Não é necessário instalar bibliotecas nem conectar à Internet.

## Como entregar

Sugestão: envie a pasta do projeto ou publique os arquivos em **um novo repositório GitHub para a Aula 09**, mantendo a atividade anterior separada. Confira o ambiente de entrega, prazo e demais orientações do professor.

> Observação: este trabalho demonstra os conceitos da aula, mas o slide de atividade não definiu número obrigatório de páginas, tema ou formato de envio.
