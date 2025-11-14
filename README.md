# Landing Page Amanda PMU

Landing page estática para apresentar os serviços de Amanda PMU e permitir que as clientes montem um ritual de beleza e confirmem o agendamento pelo WhatsApp.

## Como visualizar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno.
3. Caso exista algum atalho antigo apontando para `index.html.html`, ele redireciona automaticamente para a nova versão.

## Experiência da página

- **Paleta**: degradê verde #BCD054 com nuances champanhe e branco, mantendo a identidade elegante do estúdio.
- **Hero**: título “Amanda PMU”, destaque para “Montar ritual agora” e vitrine animada com partículas douradas.
- **Serviços**: grade responsiva gerada via JavaScript, com cartões animados, ícones SVG e múltipla seleção.
- **Resumo**: painel lateral exibe os serviços escolhidos, total estimado e campos para nome, dia (segunda a sábado) e horário preferido.
- **WhatsApp**: o botão “Confirmar pelo WhatsApp” monta a mensagem com todos os itens selecionados, inclui o valor total e envia para o número oficial `55 71 98399-6400`.

## Personalização

- Para alterar textos, preços ou descrições, ajuste a lista `servicesData` no final do `index.html`.
- Os valores dos serviços estão definidos na propriedade `price` de cada item do array.
- A lista de dias pode ser ajustada editando as opções do `<select id="preferred-day">`.
- Os ícones dos serviços são SVGs inline (nenhum arquivo binário é necessário). Você pode adaptar os traços dentro de cada `<svg>` conforme preferir.

## Testing

⚠️ Não há testes automatizados para projetos estáticos; basta abrir o `index.html` no navegador para validar o funcionamento.
Este repositório contém a landing page estática desenvolvida para divulgar os serviços de Amanda PMU e permitir o agendamento via WhatsApp.

## Como visualizar a página

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` diretamente no seu navegador (caso ainda tenha um atalho antigo, o arquivo `index.html.html` redireciona automaticamente para a versão nova).
3. Preencha o formulário informando seu nome, os dias e horários desejados e marque um ou mais serviços para montar o combo ideal.
4. Acompanhe o **Resumo do agendamento**, que lista os serviços marcados e soma o total estimado em tempo real.
5. Clique em **Agendar pelo WhatsApp** para abrir o aplicativo com a mensagem pronta — ela já inclui todos os serviços selecionados, o valor estimado e direciona para o número oficial (55 71 98399-6400).

## Estrutura dos arquivos

- `index.html`: página principal com o layout em verde #BCD054, animações suaves e formulário de agendamento.
- retrato da Amanda incorporado diretamente no `index.html` via Data URL, dispensando pastas externas de imagem.
- `README.md`: este guia rápido com as instruções de uso.

## Sobre a seção "Testing"

Como este projeto é um site estático (apenas HTML, CSS e JavaScript), não há testes automatizados configurados. Por isso, sempre que vir o item **Testing** com a mensagem `⚠️ Not run (static site)`, significa apenas que não há testes automáticos para executar; o comportamento é verificado manualmente abrindo o `index.html` no navegador.

## Personalizações futuras

Caso seja necessário ajustar textos, preços, imagens ou o número de WhatsApp, basta editar o arquivo `index.html` e recarregar a página no navegador para ver as alterações.
