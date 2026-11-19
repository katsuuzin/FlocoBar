# FlocoBar

FlocoBar é uma ilha flutuante para Windows, no estilo do "notch": uma pílula no topo da tela que mostra a hora e, ao passar o mouse, se abre num painel com ferramentas do dia a dia. Ele também traz um mixer de volume por aplicativo.

Feito sobre o Volum v0.8.1 (licença MIT), com WinForms e WebView2 em .NET 8.

## O que ele faz

- **Ilha com abas:** player de mídia, pomodoro, área de transferência, controles do sistema, notificações, prateleira de arquivos, chamadas, iniciador de apps, widgets e navegador.
- **Área de transferência:** histórico de textos e imagens, aviso quando um print é copiado e opção de baixar vídeos copiados (YouTube, TikTok, X) em qualidade máxima, 1080p, MP3 ou WAV.
- **Captura de região (estilo Lightshot):** recorte com lápis, linha, seta, retângulo, marca-texto, texto, cores e espessuras. Mostra o texto da imagem (OCR do Windows) para selecionar e copiar.
- **Recursos extras:** barra de tarefas própria, relógio do dia, faixa de jogos, atalhos globais, bichinho da ilha, celular como controle (QR code) e 8 temas que também mudam a janela de Configurações.
- **Atualização automática:** o app verifica as versões publicadas aqui e se atualiza sozinho.

## Instalar

Baixe o `FlocoBar-win-Setup.exe` na [última versão](../../releases/latest). Ele instala só para o seu usuário, sem administrador. Existe também a versão portátil (`FlocoBar-win-Portable.zip`).

O programa não é assinado digitalmente, então o Windows SmartScreen pode avisar na primeira vez: "Mais informações" e depois "Executar assim mesmo". O .NET já vem junto; o WebView2 já vem no Windows 10 e 11.
