# Dados por desenvolvedor

Cada desenvolvedor deve publicar seu JSON no arquivo correspondente na raiz do repositório:

| Desenvolvedor | Arquivo |
| --- | --- |
| Miguel Marques | `demandas.json` |
| Ramon Pacheco | `demandas-ramon.json` |
| Gabriel Macial | `demandas-gabriel.json` |
| Guilherme Pardo | `demandas-guilherme.json` |

Os arquivos devem manter o formato `schemaVersion: 1`, com `generatedAt` e a lista `demands`. Os três arquivos novos começam vazios e podem ser substituídos pelo JSON exportado de cada planilha.

O painel solicita a chave cadastrada para o nome escolhido antes de carregar o respectivo arquivo. Como o site e os arquivos ficam públicos no GitHub Pages, esse passo serve apenas como bloqueio visual: não impede que alguém leia o HTML, encontre as chaves ou acesse os JSONs diretamente.
