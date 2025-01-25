# jubilant-octo-robot
1. Importação e Configuração: Importa bibliotecas necessárias e baixa/descompacta imagens de validação e anotações do COCO dataset.
2. Configuração do Caminho e Instância COCO: Define o diretório dos arquivos e carrega as anotações do COCO.
3. Processamento de Imagens:
   - Carrega IDs e Anotações: Obtém IDs de imagens e anotações das categorias "person" e "car".
   - Download da Imagem:  Baixa uma imagem aleatória contendo "person" ou "car".
   - Desenha Rótulos: Filtra anotações para "person" e "car", desenha caixas e rótulos na imagem.
4. Exibição da Imagem: Exibe a imagem com rótulos usando Matplotlib.
