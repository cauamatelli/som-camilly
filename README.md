# SOUND ALERT 🔊

Medidor de ruído em tempo real com Web Audio API. Tudo roda no navegador, sem gravar nem enviar áudio.

## Como executar
1. Abra a pasta no VS Code.
2. Instale a extensão **Live Server** (Ritwick Dey).
3. Clique com o botão direito em `index.html` > **Open with Live Server**.
   O microfone funciona em `localhost` ou HTTPS.

Sem Live Server: `python -m http.server 8000` na pasta e abra http://localhost:8000

## Como publicar de graça
- **Netlify Drop:** arraste a pasta em https://app.netlify.com/drop
- **GitHub Pages:** envie os arquivos ao GitHub e ative Settings > Pages.

Obs.: os valores são em dBFS (escala relativa), não em dB SPL. Não é um decibelímetro profissional.
