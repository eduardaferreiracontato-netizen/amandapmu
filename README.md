# Landing Page Amanda Sampaio

Landing page estática para apresentar os serviços de Amanda Sampaio e permitir que as clientes montem um ritual de beleza e confirmem o agendamento pelo WhatsApp.

## Como visualizar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno.

## Experiência da página

- **Paleta**: degradê verde-água e dourado suave (#BCD054) com fundo branco iluminado.
- **Hero**: destaque “Amanda Sampaio” com tipografia degradê flutuante e sem foto na capa, mantendo a chamada “Montar ritual agora”.
- **Serviços**: grade responsiva gerada via JavaScript, com ilustrações fotográficas embutidas em SVG e múltipla seleção.
- **Portfólio**: álbum rolante automático ao final da página destacando resultados recentes com fotos reais carregadas por URL.
- **Resumo**: painel lateral exibe os serviços escolhidos, total estimado e campos para nome, dia (segunda a sábado) e horário preferido.
- **WhatsApp**: o botão “Confirmar pelo WhatsApp” monta a mensagem com todos os itens selecionados, inclui o valor total e envia para o número oficial `55 71 98399-6400`.
- **Arquivo único**: o site inteiro está no `index.html`, encerrando corretamente com um único rodapé e sem blocos de patch adicionais.

## Personalização

- Para alterar textos, preços ou descrições, ajuste a lista `servicesData` no final do `index.html`.
- Os valores dos serviços estão definidos na propriedade `price` de cada item do array.
- A lista de dias pode ser ajustada editando as opções do `<select id="preferred-day">`.
- As imagens dos serviços continuam sendo ilustrações SVG inline (para evitar arquivos binários), enquanto o álbum final usa URLs de fotos reais definidas na função `populateGallery` ao final do `index.html`. Troque os links dessa lista para usar suas próprias fotos; por serem remotas, não é preciso fazer upload de binários.
- Basta manter apenas o conteúdo do `index.html` (não há scripts extras para limpar rodapés duplicados) para preservar o layout.

## Testing

⚠️ Não há testes automatizados para projetos estáticos; basta abrir o `index.html` no navegador para validar o funcionamento.
