# CarniFit — estrutura fiel do funil

Quiz mobile-first estático com as 36 telas e a ordem estrutural mapeadas do funil de referência, preparado para publicação na Vercel.

Os espaços de imagens e comentários estão identificados no código para receber os materiais autorizados enviados pelo cliente.

O checkout já está conectado a `https://pay.wiapy.com/KX2LK3vXNU`.

## Configuração

Edite o objeto `CONFIG` no início de `app.js` para alterar checkout, preço, marca e futuros códigos de rastreamento.

Todos os parâmetros UTM e `fbclid` recebidos na entrada são mantidos durante o quiz e anexados ao checkout.

## Publicação na Vercel

O projeto não exige comando de build nem diretório de saída. Na importação do repositório, mantenha o framework como `Other` e deixe `Build Command` e `Output Directory` vazios.
