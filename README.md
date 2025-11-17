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
