# Documento Word para Texto com Tratamento e Conversão
Este script automatiza o processo de conversão de um documento Word .docx para um arquivo de texto .txt, realizando tratamento no texto (remoção de espaços em excesso) e convertendo novamente o texto tratado para um documento Word. Ele é útil para padronizar e tratar o conteúdo textual de documentos.
## Como funciona
### Entrada:
Lê o conteúdo de Capitulo 1.docx.
### Processamento:
Verifica se Capitulo 1.txt existe:
Sim: Trata o texto, removendo espaços e linhas extras.
Não: Cria o arquivo a partir do Word.
### Saída:
Gera um documento Word tratado (DocxTratado.docx) com texto limpo.
## Requisitos
### Bibliotecas:
python-docx (pip install python-docx)
os, re (padrão do Python)
## Como usar
Coloque Capitulo 1.docx na mesma pasta do script.
Execute o script.
### Confira os arquivos gerados:
Texto tratado: Capitulo 1.txt
Documento Word tratado: DocxTratado.docx
## Observação
Linhas vazias e espaços extras são removidos automaticamente.
