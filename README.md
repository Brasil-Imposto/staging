# Brasil-Imposto/staging

Este repositório só publica o site de staging do Brasil-Imposto em <https://brasil-imposto.github.io/staging/>. Ele não guarda
código nem arquivos montados: o workflow `.github/workflows/deploy.yml` busca o ramo `staging` de
<https://github.com/Brasil-Imposto/brasil-imposto.github.io>, monta o perfil de staging e publica no GitHub Pages deste
repositório.

O staging é o ambiente de ideias: todo pull request entra primeiro nele, com todas as funcionalidades ligadas; a produção, em
<https://brasil-imposto.github.io>, mostra só o que foi aprovado. A fonte do workflow é `deploy/staging/deploy.yml` no repositório
principal, revisada por pull request, e a spec é `docs/superpowers/specs/BRASIL-IMPOSTO_SPEC_staging_2026-10-23.md`.

Mudanças entram por pull request, como no repositório principal.
