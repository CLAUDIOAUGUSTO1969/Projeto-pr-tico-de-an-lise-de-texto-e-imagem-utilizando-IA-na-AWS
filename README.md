# Análise Avançada de Imagens e Texto com IA na AWS

Este repositório contém um projeto prático que utiliza os serviços da AWS, como **Amazon Textract** e **Amazon Transcribe**, para análise de imagens e transcrição de áudio. O objetivo é automatizar a extração de texto de documentos e transcrições de chamadas de clientes.
## Tecnologias Utilizadas
- **Amazon Textract**: Para extração de texto de documentos e imagens.
- **Amazon Transcribe**: Para transcrição de áudio em tempo real.
- **Python (Boto3)**: Para interagir com os serviços da AWS.
- **AWS Lambda**: Para automação do processo.
- **S3**: Para armazenar arquivos de entrada e saída.
## Fluxo de Trabalho

1. O usuário envia documentos ou áudios para o **Amazon S3**.
2. O serviço **Amazon Textract** é acionado para extrair texto de arquivos de imagem ou PDF.
3. Se o arquivo for um áudio, o **Amazon Transcribe** realiza a transcrição em tempo real.
4. O texto extraído ou transcrito é armazenado no **S3** ou em um banco de dados para análise posterior.
## Como Rodar o Projeto

1. Clone este repositório para o seu computador:
```bash
git clone https://github.com/SeuUsuario/aws-image-text-analysis.git
pip install boto3
aws configure
## Possíveis Melhorias
- Aperfeiçoamento na extração de dados para documentos complexos.
- Suporte a mais idiomas para transcrição de áudios.
- Implementação de análise de sentimentos nas transcrições.
