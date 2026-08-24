# CyberKid Policies

Repositório **público** que hospeda as políticas de privacidade dos aplicativos da
CyberKid Studios. Existe apenas para servir essas páginas via GitHub Pages — não
contém código-fonte de nenhum app.

## URLs publicadas

| App | URL da política |
|---|---|
| Smart Reps | https://euclidespaim.github.io/cyberkid-policies/smart-reps/ |
| Async Runner | https://euclidespaim.github.io/cyberkid-policies/async-runner/ |
| PyQuest | https://euclidespaim.github.io/cyberkid-policies/pyquest/ |
| Neon Blocks | https://euclidespaim.github.io/cyberkid-policies/neon-blocks/ |

São essas as URLs que devem constar na ficha de cada app no Google Play Console.

## Estrutura

Uma pasta por app, cada uma com seu próprio `index.html`. O `favicon.svg` na raiz
é compartilhado (referenciado como `../favicon.svg`).

## Regra

Nada além de HTML/CSS estático de política entra aqui. O código-fonte dos apps
vive em repositórios **privados** separados:
`smart-reps`, `async-runner-app`, `neon-blocks-app`, `pyquest`.

## URLs antigas

Os repositórios `async-runner`, `neon-blocks`, `pyquest2.0` e a branch `gh-pages`
de `smart-reps` foram convertidos em redirecionamentos para as URLs acima, de modo
que links já registrados na Play Store continuem funcionando. Podem ser removidos
depois que todas as fichas do Play Console estiverem atualizadas.
