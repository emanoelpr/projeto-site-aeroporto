# Aeroporto Municipal Prefeito José Cleto

Este projeto foi preparado para estudo e apresentação no modulo **Desenvolvimento Web**. Ele usa **somente HTML e CSS**. Não existe arquivo JavaScript e nenhuma página carrega scripts pelo desafio imposto no modulo.

## Arquivos

- `index.html` — página inicial.
- `voos.html` — tabela com voos fictícios para aprender tabelas HTML.
- `servicos.html` — cartões com exemplos de serviços.
- `sobre.html` — apresentação do aeroporto e espaço para dados técnicos.
- `informacoes.html` — perguntas frequentes que abrem e fecham com os elementos HTML `details` e `summary`.
- `styles.css` — cores, tamanhos, posicionamento e adaptação para celular.

## Como abrir

1. Extraia a pasta do arquivo ZIP.
2. Abra a pasta no Visual Studio Code.
3. Abra `index.html` no navegador. Você também pode usar a extensão Live Server, caso já tenha essa extensão instalada.
4. Clique nos links do menu para navegar entre as páginas.

O site não precisa de servidor nem de instalação de bibliotecas. Basta abrir o arquivo HTML no navegador.

## Como explicar o projeto

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
- `<footer>` contém o rodapé.

### CSS
CSS controla a aparência do conteúdo HTML.

- `:root` guarda as cores em variáveis, para reaproveitá-las.
- `background-color` define a cor de fundo.
- `color` define a cor do texto.
- `padding` cria espaço dentro de um elemento.
- `margin` cria espaço fora de um elemento.
- `display: flex` organiza elementos em uma linha ou coluna.
- `display: grid` organiza elementos em colunas e linhas.
- `border-radius` arredonda os cantos.
- `@media` muda o layout em telas menores, como celulares.

### Como as páginas se conectam?
Cada página possui links como `href="servicos.html"`. Ao clicar, o navegador abre o arquivo indicado. O mesmo arquivo `styles.css` é usado por todas as páginas, para que elas tenham a mesma aparência.

## Limitações intencionais desta versão

Como não há JavaScript nem servidor, os voos são exemplos fixos: não há busca, filtros, paginação automática, tradução automática ou clima em tempo real. Os cartões e as páginas são demonstrativos. Os dados oficiais do aeroporto devem ser verificados antes de qualquer publicação institucional.


## Mapas externos (sem JavaScript)

- `voos.html` incorpora um mapa de rastreamento de aeronaves do Flightradar24, centrado na região de União da Vitória. Se o provedor bloquear a incorporação no navegador, há um link para abrir o mapa externo. A cobertura regional pode ser limitada.
- `informacoes.html` incorpora o mapa meteorológico do Windy, também centrado em União da Vitória. O mapa depende de conexão com a internet.
- As incorporações usam apenas HTML (`iframe`) e CSS; o projeto não inclui JavaScript próprio. Serviços externos podem alterar suas políticas de incorporação ou exigir condições de uso específicas.
- O mapa de aeronaves não deve ser tratado como painel oficial de partidas e chegadas, e o mapa meteorológico não substitui avisos oficiais nem informações operacionais do aeroporto.
