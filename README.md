# Landing Page Amanda PMU

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
