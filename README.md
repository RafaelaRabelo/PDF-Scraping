# PDF Scraping usando Python

## Descrição das Etapas

1. **Definir diretório de entrada**: Especificar o local onde os PDFs estão armazenados.
2. **Para cada PDF**: Iterar sobre cada arquivo PDF no diretório.
   - **Abrir PDF**: Utilizar a biblioteca `fitz` para abrir o arquivo PDF.
   - **Extrair texto**: Usar `fitz` para extrair o texto contido no PDF.
   - **Processar texto**: Realizar quaisquer operações necessárias no texto extraído.
   - **Armazenar dados extraídos**: Guardar os dados em uma estrutura apropriada.
3. **Salvar dados em arquivo**: Escrever os dados processados em um arquivo para armazenamento.

