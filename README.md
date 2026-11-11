# Aeroporto Municipal Prefeito José Cleto

**Autor**: Emanoel do Prado

Este projeto foi desenvolvido para estudo e apresentação no módulo Desenvolvimento Web. O site utiliza exclusivamente HTML5 e CSS3, sem JavaScript, conforme as exigências propostas para a atividade.

O objetivo é apresentar um modelo de site institucional de aeroporto, com páginas informativas, tabelas demonstrativas, cartões de serviços, perguntas frequentes e incorporações de mapas externos.

## Arquivos

- `index.html` — página inicial.
- `voos.html` — tabela com voos fictícios para aprender tabelas HTML.
- `servicos.html` — cartões com exemplos de serviços.
- `sobre.html` — apresentação do aeroporto e espaço para dados técnicos.
- `informacoes.html` — perguntas frequentes que abrem e fecham com os elementos HTML `details` e `summary`.
- `styles.css` — cores, tamanhos, posicionamento e adaptação para celular.
- `imagens/` — pasta destinada às imagens utilizadas como planos de fundo das seções.

## Como abrir

1. Extraia a pasta do arquivo ZIP.
2. Abra a pasta no Visual Studio Code.
3. Abra `index.html` no navegador. Você também pode usar a extensão Live Server, caso já tenha essa extensão instalada.
4. Clique nos links do menu para navegar entre as páginas.

O site não precisa de servidor nem de instalação de bibliotecas. Basta abrir o arquivo HTML no navegador.

## Como o projeto funciona

### HTML
HTML organiza o conteúdo. Por exemplo:

- `<header>` contém o cabeçalho.
- `<nav>` contém os links de navegação.
- `<main>` identifica o conteúdo principal da página.
- `<section>` agrupa uma parte do conteúdo.
- `<article>` é usado para cartões que apresentam um assunto.
- `<a href="voos.html">` cria um link para outra página.
- `<table>`, `<tr>`, `<th>` e `<td>` montam a tabela de voos.
- `<details>` e `<summary>` criam perguntas que podem ser abertas e fechadas sem JavaScript.
- `<iframe>` permite incorporar conteúdos externos, como mapas.
- `<footer>` contém o rodapé.

### CSS
CSS controla a aparência do conteúdo HTML.

- `:root` guarda as cores em variáveis, para reaproveitá-las.
- `background-color` define a cor de fundo.
- `background-image` permite utilizar imagens e gradientes como fundo.
- `color` define a cor do texto.
- `padding` cria espaço dentro de um elemento.
- `margin` cria espaço fora de um elemento.
- `display: flex` organiza elementos em uma linha ou coluna.
- `display: grid` organiza elementos em colunas e linhas.
- `border-radius` arredonda os cantos.
- `text-shadow` adiciona sombra ao texto para melhorar sua leitura sobre imagens.
- `@media` muda o layout em telas menores, como celulares.

### Como as páginas se conectam?
Cada página possui links como `href="servicos.html"`. Ao clicar, o navegador abre o arquivo indicado. O mesmo arquivo `styles.css` é usado por todas as páginas, para que elas tenham a mesma aparência.

### Imagens e gradientes

Algumas seções utilizam imagens como plano de fundo, acompanhadas de gradientes escuros.

O gradiente é aplicado sobre a imagem para melhorar o contraste e facilitar a leitura dos títulos e textos. As imagens são organizadas na pasta imagens/ e referenciadas diretamente pelo CSS.

## Limitações intencionais desta versão

Como não há JavaScript nem servidor, os voos são exemplos fixos: não há busca, filtros, paginação automática, tradução automática ou clima em tempo real. Os cartões e as páginas são demonstrativos. Os dados oficiais do aeroporto devem ser verificados antes de qualquer publicação institucional.

- Os voos apresentados são exemplos fictícios e fixos.
- Não existe busca ou filtragem automática de voos.
- Não há atualização automática de horários ou situações de embarque.
- Não existe sistema real de compra ou reserva de passagens.
- Não há tradução automática.
- As informações meteorológicas e de rastreamento dependem de serviços externos.

## Mapas externos (sem JavaScript)

- `voos.html` incorpora um mapa de rastreamento de aeronaves do ADS-B Exchange, centralizado na região de União da Vitória (PR). O mapa utiliza as coordenadas geográficas da região e permite visualizar aeronaves identificadas pelo serviço.
- `informacoes.html` incorpora o mapa meteorológico do Windy, também centrado em União da Vitória. O mapa depende de conexão com a internet.
- As incorporações usam apenas HTML (`iframe`) e CSS; o projeto não inclui JavaScript próprio. Serviços externos podem alterar suas políticas de incorporação ou exigir condições de uso específicas.
- O mapa de aeronaves não deve ser tratado como painel oficial de partidas e chegadas, e o mapa meteorológico não substitui avisos oficiais nem informações operacionais do aeroporto.

## Objetivo educacional

O projeto permite praticar conceitos fundamentais de desenvolvimento web, incluindo estruturação semântica com HTML, estilização com CSS, organização de arquivos, navegação entre páginas, tabelas, elementos interativos nativos do HTML e adaptação de layouts para diferentes dispositivos.
