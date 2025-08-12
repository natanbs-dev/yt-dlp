# YT-DLP | TERMINAL COMMANDS

## COMMANDS

#### bestaudio&bestvideo:
yt-dlp -f bestvideo*+bestaudio/best <URL>
*or
yt-dlp <URL>

#### Priorizando áudio de alta qualidade:
yt-dlp -f "bestaudio[ext=m4a]" https://youtu.be/K6PwUG283DU

#### listar os formatos disponíveis 
yt-dlp -F <URL>

#### 1080p 60fps download video
yt-dlp -f "bestvideo[height<=1080][fps>=60]+bestaudio/best[height<=1080][fps>=60]" <URL>


## INSTALAÇÃO

- linux: utilizar do gerenciador de pacotes para instalar e utilizar pelo terminal
