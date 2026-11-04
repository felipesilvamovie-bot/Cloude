# VZN QG — escritório virtual da VZN Agência

Chat por canais, salas de voz, câmera e compartilhamento de tela, no estilo Discord.
É grátis, sem servidor e sem nenhuma IA: as pessoas se conectam direto umas com as outras (WebRTC, P2P).

- Senha de entrada: `vzn` (maiúscula ou minúscula, tanto faz)
- Cada pessoa escolhe nome e bonequinho na primeira vez. Depois entra direto.

## Como colocar no ar (uma vez só)
1. No GitHub, abra este repositório → **Settings** → **Pages**.
2. Em **Branch**, escolha `claude/vigilant-gauss-1ofn9f` e a pasta `/ (root)`, depois clique em **Save**.
3. Em 1–2 minutos o link aparece no topo da página (algo como `https://felipesilvamovie-bot.github.io/Cloude/`).
4. Mande o link + a senha para a equipe.

## Limites (por ser sem servidor)
- Cada sala de voz funciona bem com até ~5–6 pessoas de câmera ligada. Só voz ou só uma tela compartilhada aguenta mais.
  Dá para espalhar a equipe pelas 5 salas.
- O histórico do chat fica salvo nos computadores de quem usa e é sincronizado quando alguém entra.
  Mensagens mandadas quando você estava offline chegam se alguém que as recebeu estiver online.
- Em redes com firewall muito fechado a conexão direta pode falhar.
- Compartilhar a tela funciona no computador (Chrome, Edge, Firefox). No celular dá para usar chat, voz e câmera.

## Personalizar
Canais, salas e senha ficam no topo do script em `index.html` (bloco "CONFIGURAÇÃO").
