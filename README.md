# Chrome-Extension-Instagram-Voice-Tool
Um script CLI de nó simples para instagram DM.

A ideia para este script CLI é inspirada no correio de voz tradicional. Por baixo dela, esta biblioteca está usando [Instagram MQTT] (https://github.com/Nerixyz/instagram_mqtt) e [Instagram Private API] (https://github.com/dilame/instagram-private-api)

**Como usar**

Baixe ou clone o repositório, navegue até a pasta criada e instale as dependências do projeto
```
npm install
```
Antes de executar o script, crie uma nova pasta e chame-a de `media` dentro da pasta do projeto. Ele conterá todas as mensagens de áudio que serão enviadas a você quando o script estiver em execução.

Para usar o bot de correio de voz, você precisa ter a biblioteca `ffmpeg` instalada em seu sistema. Coloque dentro da pasta de script um arquivo `mp3` chamado` voicemail.mp3`. O script, quando você optar por habilitar o bot, irá procurar por esse arquivo e terá o cuidado de convertê-lo para o formato de áudio aceito pelo Instagram. Certifique-se de usar apenas arquivos com duração máxima de 1:00 minutos.

Para substituir sua mensagem de correio de voz, simplesmente substitua o arquivo `voicemail.mp3` e exclua o arquivo` voicemail.mp4` gerado automaticamente.

Rode o script
```
node index.js
```
**Atualizações futuras**

Adicionar função para gravar e enviar audios pelo Instagram Desktop. 

**Esta função irá auxiliar os produtores de marketing digital para automatizar suas vendas pelo direct do instagram, podendo enviar e encaminhar audios para inúmeros clientes.**

****AVISO LEGAL****

Este script é seguro para uso. Suas credenciais do Instagram serão usadas a partir do script apenas para login. Nenhum dado é compartilhado online ou com servidor de terceiros. Tenha cuidado durante o uso, não sou responsável se sua conta for bloqueada por atividades de spam.

