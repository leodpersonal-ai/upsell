# VetDosis — página de upsell

Página estática em espanhol para oferecer a calculadora de doses após a compra dos 150 flashcards. Inclui o vídeo fornecido pelo proprietário, convertido para MP4 compatível com celulares.

## Prévia local

Execute `python3 -m http.server 8080` na raiz do projeto e abra `http://localhost:8080`.

## Integração Hotmart pendente

Insira o widget oficial de aceite e recusa no elemento `#hotmart-offer` em `index.html`, com os scripts, identificadores e destinos fornecidos pela Hotmart. O espaço fica oculto enquanto está vazio, sem botões fictícios ou redirecionamentos.

O preço não foi informado e não está publicado. Ao recebê-lo, inclua o preço e as condições da oferta junto ao widget. Depois de hospedar a página, configure sua URL como etapa de upsell no funil Hotmart e valide aceite e recusa com o fluxo de teste da plataforma.

## Publicação

Publique a raiz do repositório em uma hospedagem estática. Não há dependências nem etapa de build. Preserve a pasta `assets` junto de `index.html` e `styles.css`.
