# Duel Data Extractor

![Yu-Gi-Oh! Duel Links Logo](https://mnd-assets.mynewsdesk.com/image/upload/c_fill,dpr_auto,f_auto,g_auto,q_auto:good,w_746/wzbnpvpe38955662ao9e) <!-- Adicione uma imagem temática -->

Um projeto para extrair e estruturar dados das cartas do jogo **Yu-Gi-Oh! Duel Links** (Steam) de forma automatizada, utilizando técnicas de automação, processamento de imagem e OCR.

---

## 🚀 Funcionalidades

- **Automação**: Captura automática de imagens das cartas no jogo.
- **Processamento de Imagens**: Pré-processamento de imagens para melhorar a qualidade do OCR.
- **OCR**: Extração de texto das cartas usando Tesseract.
- **Estruturação de Dados**: Armazenamento dos dados em formato JSON ou CSV.
- **Escalável**: Projetado para processar milhares de cartas de forma eficiente.

---

## 📦 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/rafaelsantos999/Duel-Links-Cards-Extractor.git

2. Instale as depêndencias
    ```bash
    pip install -r requirements.txt

3. Configure o Tesseract OCR
    * Baixe e Instale o Tesseract no seu sistema.
    * Defina o caminho do executável no script
        ```bash
        pytesseract.pytesseract.tesseract_cmd = r'Caminho\Para\Tesseract-OCR\tesseract.exe'

## Como Usar

1. Execute o script principal
    ```bash
    python src/main.py
2. Siga as instruções no terminal para capturar e processar as cartas.
3. Os dados extraídos serão savos em data/cards.json
