# CSM Visualizador XML — canal oficial de atualização

Este diretório controla o canal de atualização do **CSM Visualizador XML**.

- Marco estável atual: **3.7.7**
- Manifesto consumido pelo aplicativo: `latest.json`
- O aplicativo valida versão, HTTPS e SHA-256 antes de iniciar uma atualização.
- A partir da linha 3.7.8, o CSM também verifica automaticamente este canal ao iniciar e abre a tela de atualização quando houver uma versão mais nova.

## Política de publicação

1. Uma versão só entra em `latest.json` depois de validada.
2. O pacote de atualização deve ser servido por HTTPS.
3. O SHA-256 publicado deve corresponder exatamente ao pacote.
4. A versão estável anterior é mantida como ponto de restauração.

Criado por Marques — CSM / Contabilidade São Mateus.
