# Organizador de pasta
Este script organiza arquivos em um diretório especificado, movendo-os para pastas baseadas em suas extensões.

## Funcionalidades

- Organiza arquivos de áudio (`.mp3`, `.wav`) em uma pasta `audios/`.
- Organiza arquivos de vídeo (`.mp4`, `.mov`, `.avi`) em uma pasta `videos/`.
- Organiza imagens (`.jpg`, `.jpeg`, `.png`) em uma pasta `images/`.
- Organiza documentos (`.txt`, `.pdf`, `.zip`) em uma pasta `documents/`.
- Arquivos que não se encaixam nas categorias acima são movidos para a pasta `others/`.

## Pré-requisitos

- Python 3.x
- Biblioteca `pathlib` e `os` (bibliotecas padrão do Python)

## Como Usar

1. Clone ou faça o download deste repositório.
2. Navegue até o diretório do projeto.
3. Execute o script main.py:

```bash
python main.py
```

4. Insira o caminho absoluto para o diretório que você deseja organizar quando solicitado.

## Personalização

Você pode personalizar as extensões de arquivos organizados editando as listas ``AUDIOS_EXT``, ``VIDEOS_EXT``, ``IMAGES_EXT``, e ``DOCUMENTS_EXT`` no arquivo ``main.py``.
