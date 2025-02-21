📄 AWS Textract - Desafio

📌 Visão Geral

O AWS Textract é um serviço de Machine Learning que permite extrair texto, tabelas, formulários e assinaturas de documentos digitalizados. Este desafio consiste em utilizar a funcionalidade "Analisar documento" do AWS Textract para processar arquivos de imagem ou PDF e extrair informações estruturadas.

🚀 Fluxo de Trabalho

1️⃣ Escolha um documento

✅ Utilize um dos documentos de amostra fornecidos pela AWS (ex.: Paystub) ou carregue seu próprio arquivo.
✅ Os arquivos devem obedecer aos seguintes requisitos:

Formatos suportados: JPEG, PNG, PDF

Tamanho máximo: 5 MB

**Máximo de 11 páginas` por documento

2️⃣ Fazer upload do documento

📂 Clique na opção "Upload de documento" e selecione o arquivo desejado ou arraste e solte diretamente na interface.
⏳ O sistema processará o documento e apresentará os resultados automaticamente.

3️⃣ Analisar os Resultados

🧐 A interface do AWS Textract exibe os dados extraídos organizados em diferentes categorias:

📜 Texto simples: Extração de texto bruto

📐 Layout: Estruturação baseada em posicionamento do conteúdo

📝 Formas: Detecção de formulários e preenchimentos

📊 Tabelas: Identificação de tabelas e células

✍️ Assinaturas: Reconhecimento de assinaturas digitais ou manuscritas

4️⃣ Verificação de Confiança

📊 Cada trecho extraído recebe uma pontuação de confiança.
🔹 Exemplo:

"Filtro para café" - Confiança: 92%
"Papel alumínio" - Confiança: 90%

✅ Quanto maior a pontuação, mais preciso é o reconhecimento do conteúdo.

5️⃣ Download dos Resultados

📥 O AWS Textract permite baixar os dados extraídos em formato CSV para análise posterior.
📑 Também é possível processar documentos em lote (até 150 documentos por solicitação).

6️⃣ Restaurar a Demonstração

♻️ Caso queira testar novamente, utilize a opção "Restaurar demonstração", que retorna a interface para o estado inicial.

📊 Exemplo de Saída

Após o processamento, o documento analisado retorna um resultado estruturado como:

Header 1 (Confiança: 52%)
  lista de
Header 2 (Confiança: 45%)
  PRIMEIRA COMPRA
Title 1 (Confiança: 46%)
  UTILIDADES
Text 1 (Confiança: 33%)
  ITENS IMPORTANTES
Text 2 (Confiança: 45%)
  Guardanapos de papel
Text 3 (Confiança: 78%)
  Papel toalha
...

🎯 Conclusão

Este desafio permite explorar as capacidades do AWS Textract na extração e estruturação de informações a partir de documentos digitalizados. A análise dos resultados e das pontuações de confiança pode ajudar na automação de fluxos de trabalho envolvendo OCR (Reconhecimento Óptico de Caracteres) e análise documental em grande escala.

📢 Dúvidas ou sugestões? Contribua com este repositório! 🚀

