# Dados por desenvolvedor

Cada desenvolvedor deve publicar o JSON exportado da sua planilha na raiz da branch `main`, usando o nome correspondente:

| Desenvolvedor | Arquivo no repositório |
| --- | --- |
| Miguel Marques | `demandas-miguel.json` |
| Ramon Pacheco | `demandas-ramon.json` |
| Gabriel Macial | `demandas-gabriel.json` |
| Guilherme Pardo | `demandas-guilherme.json` |

O arquivo baixado da planilha pode se chamar `demandas.json`. Antes de enviar, renomeie-o conforme a tabela acima ou informe esse nome ao carregar o arquivo no GitHub. Substitua somente o JSON da própria pessoa; não junte os arquivos nem substitua o arquivo de outro desenvolvedor.

O painel usa a pessoa escolhida no popup para carregar automaticamente o arquivo associado. Os JSONs devem manter o formato exportado com `schemaVersion: 1`, `generatedAt` e a lista `demands`. Os arquivos de Ramon, Gabriel e Guilherme começam vazios e podem ser substituídos pelas exportações correspondentes.

Como o site e os dados ficam públicos no GitHub Pages, o popup de chave é apenas um bloqueio visual; ele não impede que alguém leia o código ou acesse diretamente os arquivos JSON.
