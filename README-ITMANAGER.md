# Artefato FFmpeg para o IT Manager

Este repositório mantém versões aprovadas e imutáveis do FFmpeg usadas pelo Windows Agent.

## Política de versionamento

- Não usar `latest` em builds do Agent.
- Cada versão deve ter manifesto, release, tag e SHA-256.
- Uma release publicada não deve ser sobrescrita.
- Atualizações devem ser feitas por uma nova versão e permitir rollback.

## Versão aprovada

- FFmpeg `8.1.2`
- Build `full_build-shared`
- Windows `x64`
- Layout de runtime: `FFmpeg/bin`
- Licença declarada pelo build: **GPLv3**

A licença e os avisos devem acompanhar os binários no pacote do Agent. A seleção GPLv3
exige revisão jurídica antes da distribuição comercial ampla do Agent.
