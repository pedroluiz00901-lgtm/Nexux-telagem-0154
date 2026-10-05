# NEXUX TELAGEM — correção WebRTC

Esta versão corrige a corrida de negociação que causava:
`Failed to set remote answer sdp: Called in wrong state: stable`

Também mantém a fila de ICE candidates e impede que o anfitrião crie ofertas duplicadas.

## Render
Build Command:
`npm install`

Start Command:
`npm start`
