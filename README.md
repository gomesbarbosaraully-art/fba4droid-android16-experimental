# fba4droid — candidato experimental para Android 16

Este repositório contém um APK experimental derivado do arquivo enviado pelo usuário.

## O que foi alterado

- O APK original identificava o app como **fba4droid 1.74**.
- O `targetSdkVersion` foi alterado de **17 para 28** como tentativa de permitir instalação em versões atuais do Android.
- As duas pastas de skins (`skin_default` e `skin_1`) foram mantidas.
- O APK foi re-assinado com uma chave de teste. Por isso, ele **não atualiza por cima** de uma instalação assinada com a chave original; pode ser necessário remover a versão antiga antes, o que pode apagar dados locais.

## Limitações importantes

Isto **não é uma atualização completa do código-fonte**. O ajuste altera somente o nível de API declarado no manifesto; não corrige bibliotecas antigas nem migra o app para as APIs modernas. O APK contém bibliotecas nativas de 32 bits (`armeabi`) e pode não funcionar em aparelhos que não aceitam apps de 32 bits.

**Não foi instalado nem testado em um aparelho/emulador com Android 16. Não há garantia de instalação ou funcionamento.** Faça backup dos dados antes de remover qualquer versão já instalada.

## Arquivo

`fba4droid-android16-experimental.apk` — build de teste, não recomendado como versão estável.
