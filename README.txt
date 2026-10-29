Sialdrill | Obras — versão corrigida

Conteúdo:
- index.html: painel web com o visual original e leitor de CSV corrigido.

Correções:
- Reconhece o cabeçalho real "Nº CHECKLIST" (normalizado como NCHECKLIST).
- Reconhece "TEM DE ESPERA".
- Reconhece o cabeçalho existente "STATUS MEIDÇÃO".
- Não inclui os registros de demonstração no carregamento inicial; se o CSV falhar, o painel não apresenta os dados de demonstração como reais.
- Mantém a atualização automática a cada 5 minutos.

Validação local executada com o CSV fornecido:
- 20 registros importados
- Aprovados: 6
- Em análise: 2
- Em produção: 7
- Finalizados: 5
- Sintaxe JavaScript validada com Node.js.

Para publicar:
1. Extraia o ZIP.
2. Substitua o index.html do repositório pelo arquivo incluído.
3. Faça commit/push para o GitHub e aguarde o deploy da Vercel.
4. Abra o site publicado e confirme a mensagem de conexão com o Google Sheets.
