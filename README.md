# [MSX-Happy-Birthday](https://github.com/tagwato/MSX-Happy-Birthday/edit/main/README.md)

Programa em Basic para o microcomputador MSX que apresenta uma animação de Feliz Aniversário personalizada com o nome do(a) aniversariante. 
Utiliza o emulador [WEBMSX](webmsx.org).  

Veja [como personalizar e usar](#como-personalizar-o-link-antes-de-enviar) ao final.

## Descrição 
O programa BASIC encontra-se neste repositório para consulta. Mas, para automatizar a carga, foi necessário carregá-lo no emulador a partir de uma imagem de disco tipo .dsk (gerada a partir do WEBMSX).  

O arquivo index.html neste repositório mostra uma tela amigável com um botão "Abrir presente". Ao ser clicado, ele chama o emulador [WEBMSX](webmsx.org) com os parâmetros adequados para setar o nome do aniversariante e rodar o programa Basic.  

O que enviar para o(a) aniversariante é o URL desta página com o nome da pessoa como parâmetro.

Para publicar o link deste repositório como página da web, FOI necessário configurar neste repositório:  
```
Settings → Pages → Build and deployment:  
  Source: Deploy from a branch  
  Branch: main  
  Folder: / (root)  
```
Salvar.  

PS - o usuário deste repositório NÃO precisa fazer o acima; isso já foi realizado.  

## Como personalizar o link antes de enviar
Basta incluir no URL do link deste repositório o parâmetro "?nome=<<nome_da_pessoa>>".  
Abaixo exemplos de links que poderiam ser enviados para o(a) aniversariante:

Mensagem genérica **sem** nome:  
https://tagwato.github.io/MSX-Happy-Birthday

Mensagem para alguém chamado Adriano:  
https://tagwato.github.io/MSX-Happy-Birthday/?nome=Adriano

Mensagem destinada à Ana Júlia:  
https://tagwato.github.io/MSX-Happy-Birthday/?nome=Ana%20Júlia

Mensagem destinada ao João Roberto:  
https://tagwato.github.io/MSX-Happy-Birthday/?nome=João%20Pedro

PS- é recomendável trocar eventuais  ESPAÇOs no nome por %20, como se vê nos 2 ultimos exemplos. Isso evita erros em certos browsers, como o Firefox.

Em síntese, para enviar um "cartão de aniversário MSX" personalizado, copie um dos links acima, coloque o nome do(a) aniversariante no parâmetro "nome" e envie para ele(a) o link ajustado!

