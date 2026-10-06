# Acompanhamento de demandas

Painel: https://admcontroles.github.io/gestao-demandas/

## Atualizar os dados do painel

1. No Excel, clique em **Gerar JSON**. A macro cria `demandas.json` e `dados.json` na pasta da planilha (ou em Downloads, se o arquivo estiver aberto diretamente do SharePoint).
2. No GitHub, abra este repositorio e clique em **Add file > Upload files**.
3. Selecione os dois arquivos gerados e envie-os para a pasta principal do repositorio, substituindo os arquivos existentes.
4. Clique em **Commit changes** para salvar a atualizacao na branch `main`.
5. Aguarde a publicacao do GitHub Pages. O painel passa a mostrar os dados novos; se ja estiver aberto, atualize a pagina ou aguarde ate cinco minutos.

O painel usa `demandas.json`. `dados.json` e uma copia de seguranca/arquivo alternativo; ambos contem o mesmo conteudo.

## Privacidade

Este repositorio e publico e o GitHub Pages tambem. Qualquer pessoa pode ver os arquivos publicados, inclusive os dados das demandas. Publique somente se esses dados estiverem autorizados para divulgacao publica. Nao envie informacoes confidenciais ou pessoais.
