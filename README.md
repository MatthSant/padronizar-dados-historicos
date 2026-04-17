# 📊 Guia Completo de Instalação e Uso do App

Este é o passo a passo para configurar sua máquina e rodar o aplicativo de análise construído com Streamlit, seja no Windows ou no Mac.

## 🚀 1. Instalando o Python (Pré-requisito)
Você precisa ter o Python instalado no seu computador para rodar o código.

**No Windows:**
1. Acesse: https://www.python.org/downloads/
2. Baixe o instalador mais recente.
3. **MUITO IMPORTANTE:** Na primeira tela do instalador, marque a caixa **"Add Python to PATH"** (ou "Adicionar Python ao PATH") no rodapé da janela. Se esquecer de marcar, o terminal não reconhecerá os comandos.
4. Clique em "Install Now" e aguarde a conclusão.

**No Mac:**
1. Acesse: https://www.python.org/downloads/ (o site já detectará o macOS).
2. Baixe e execute o instalador (macOS 64-bit universal2 installer).
3. Siga o passo a passo padrão clicando em "Continuar". 

## 🗂️ 2. Baixando o Código do Projeto
Para obter os arquivos do aplicativo prontos para uso, você só precisa baixar a pasta zipada do GitHub:

1. Acesse o link do projeto (insira o link aqui).
2. No lado direito da tela, clique no botão verde escrito **"<> Code"**.
3. No menu que abrir, clique na última opção: **"Download ZIP"**. 
4. Vá na sua pasta de Downloads, clique com o botão direito no arquivo baixado e selecione **"Extrair Tudo"** (Windows) ou dê um duplo clique no arquivo (Mac) para descompactar a pasta.
5. Deixe essa pasta extraída aberta (esta é a pasta do seu projeto).

## 📦 3. Abrindo o Terminal e Instalando Bibliotecas
Agora, você precisará usar o terminal para instalar as ferramentas que o código precisa para funcionar.

**Como abrir o terminal direto na pasta do projeto:**
* **Windows:** Na pasta que você acabou de extrair, clique na barra de endereços (lá em cima, onde mostra o caminho da pasta), apague o que estiver escrito, digite `cmd` e aperte Enter. O terminal vai abrir no lugar certinho.
* **Mac:** Clique com o botão direito (ou com dois dedos) na pasta extraída e selecione **"Novo Terminal na Pasta"** (New Terminal at Folder).

Com o terminal aberto, instale o Streamlit e o Pandas copiando e colando o comando abaixo:

```bash
pip install streamlit pandas
```
*(Nota para Mac: Se o comando acima der erro de não reconhecido, tente usar `pip3 install streamlit pandas`)*.

## ▶️ 4. Rodando o Aplicativo
Com as bibliotecas instaladas, inicie o aplicativo no mesmo terminal digitando o comando:

```bash
streamlit run app.py
```
*(Nota para Mac: Se o comando acima não funcionar, tente rodar `python3 -m streamlit run app.py`)*.

O aplicativo abrirá automaticamente em uma nova aba no seu navegador padrão (no endereço http://localhost:8501). Se fechar sem querer, basta acessar esse link!
