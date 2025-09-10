Player de Música com Pygame

Este projeto é um simples player de música em Python que utiliza a biblioteca Pygame para reproduzir uma playlist de arquivos de áudio.

Funcionalidades

- Reprodução de músicas em sequência a partir de uma playlist predefinida

- Exibição no console da música atual sendo reproduzida

- Reprodução automática da próxima música ao término da atual

Requisitos

- Python 3.x
- Biblioteca Pygame

Estrutura do Código

1. Importação de bibliotecas: Utiliza IPython.display para embedar vídeos do YouTube e Pygame para reprodução de áudio

2. Inicialização do mixer: Prepara o sistema de áudio do Pygame

3. Definição da playlist: Lista com os caminhos absolutos para os arquivos de música

4. Função tocar_playlist: Controla a reprodução sequencial das músicas

5. Loop principal: Verifica continuamente se uma música ainda está sendo reproduzida

Observações:

Os caminhos dos arquivos usam raw strings (prefixo r) para evitar problemas com caracteres especiais

O script espera o término de cada música antes de passar para a próxima

Atualmente funciona apenas com arquivos locais
