#English

For the INEP code, the extraction procedure first applies the main regex patterns. If no match is found, fallback expressions are evaluated over
the full extracted text. As a final attempt, an additional pattern is applied to the previously captured school-name segment.

The pagina field is not extracted using regular expressions. It is used only as an identifier for the processed page, allowing each set of extracted fields to be associated with its source page.

#Brazilian Portuguese

Para o código INEP, o procedimento de extração aplica inicialmente os padrões principais de regex. Caso nenhuma correspondência seja encontrada, expressões de fallback são avaliadas sobre o texto completo extraído. Como última tentativa, um padrão adicional é aplicado ao trecho previamente capturado como nome da escola.

O campo pagina não é extraído por expressão regular. Ele é utilizado apenas como identificador da página processada, permitindo associar cada conjunto de campos extraídos à sua página de origem.