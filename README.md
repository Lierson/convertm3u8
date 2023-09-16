# convertm3u8
Baixar Links M3U8 com Informações do TMDb

# Baixar Links M3U8 com Informações do TMDb

Este é um script Python que permite baixar links M3U8 de um serviço web e enriquecê-los com informações do The Movie Database (TMDb).

## Pré-requisitos

- Python 3.x instalado
- Bibliotecas Python: requests, tmdbsimple (instaladas com `pip install requests tmdbsimple`)
- Chave de API do TMDb (obtenha uma em https://www.themoviedb.org/settings/api)

## Como Usar

1. Configure sua chave de API do TMDb no arquivo `download_m3u8.py`.

2. Execute o script:

3. python download_m3u8.py


    O script irá baixar links M3U8 da API especificada, remover datas, anos entre parênteses, hífens, extensões de arquivo e "4K [HDR]" dos títulos dos filmes, buscar informações no TMDb e criar um arquivo M3U8 com os links e informações do TMDb.

## Contribuições

Contribuições são bem-vindas! Se você encontrar problemas ou tiver melhorias para sugerir, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.
