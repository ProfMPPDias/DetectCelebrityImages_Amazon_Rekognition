# Projeto DIO: Celebrity Recognition with Amazon Rekognition

Este é um projeto Python que utiliza o serviço **Amazon Rekognition** para detectar celebridades em imagens. O código identifica rostos, marca os limites dos rostos detectados e anota os nomes das celebridades diretamente nas imagens processadas.

## 📋 Funcionalidades

- Detecção automática de celebridades em imagens.
- Marcação visual com caixas delimitadoras e nomes das celebridades.
- Configuração simples para utilizar diferentes fontes e pastas de imagens.

## 🚀 Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Amazon Rekognition**: Serviço de reconhecimento de imagens.
- **Pillow (PIL)**: Para manipulação de imagens.
- **Pathlib**: Para gerenciar caminhos de arquivos.
- **boto3**: Biblioteca oficial da AWS para integração com seus serviços.

## 🛠️ Pré-requisitos

- Python 3.8 ou superior
- Uma conta AWS com permissões para o Amazon Rekognition
- Configuração do **AWS CLI** para acesso programático:
  ```bash
  aws configure
  ```
## 📦 Instalação

- **Clone o repositório:**
  
```bash  
git clone https://github.com/seu-usuario/celebrity-recognition.git
cd celebrity-recognition
```
- **Instale as dependências:**
  
```bash  
pip install -r requirements.txt
```

## 🖼️ Como Usar

- **Execute o script principal:**

```bash  
python main.py
```

## ⚙️ Configuração Opcional

- Alterar a pasta de entrada: Modifique o parâmetro folder na função get_file_path.
- Configurar o limiar de confiança: Edite o valor confidence na função annotate_image.
