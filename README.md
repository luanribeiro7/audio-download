Este projeto é um script Python que permite baixar o áudio de vídeos do YouTube e salvá-los como arquivos MP3 (ou em outro formato preferido). O script usa a biblioteca `yt-dlp` para realizar o download e a conversão.

## Funcionalidades

- Baixa o áudio do YouTube com a melhor qualidade disponível.
- Converte o áudio para MP3 (ou outro formato, se configurado).
- Organiza os arquivos de áudio na pasta especificada.

## Como Usar

1. Clone o repositório para o seu ambiente local:

    ```bash
    git clone https://github.com/luanribeiro7/youtube-to-mp3.git
    ```

2. Instale as dependências do projeto:

    O script usa a biblioteca `yt-dlp`. Para instalá-la, execute o seguinte comando:

    ```bash
    pip install yt-dlp
    ```

3. Execute o script:

    Após clonar o repositório e instalar as dependências, execute o script Python. Ele pedirá o link do vídeo do YouTube que você deseja baixar o áudio.

    ```bash
    python baixar_audio_youtube.py
    ```

4. O áudio será baixado e salvo na pasta `Youtube Music` (ou qualquer outra pasta especificada no código).

## Exemplo de uso

Ao rodar o script, ele solicitará o link do vídeo do YouTube:

```bash
Cole o link do YouTube: https://www.youtube.com/watch?v=dQw4w9WgXcQ
Baixando: https://www.youtube.com/watch?v=dQw4w9WgXcQ
Download concluído.

Feito por Luan Ribeiro