# Recomeço — instaladores oficiais

Este repositório publica **somente os instaladores** do Recomeço, ferramenta gratuita que ajuda
pessoas em recuperação do vício em apostas a bloquear sites de apostas no Windows.
O código-fonte não é publicado aqui.

- Site oficial: https://bloquear-bets.vercel.app
- Downloads: [Releases](https://github.com/davidazevedo/recomeco-releases/releases)

Criado por David Azevedo. Desenvolvido pela Aegistech.

## Como baixar com segurança

1. Baixe o instalador pelo site oficial ou pela página de [Releases](https://github.com/davidazevedo/recomeco-releases/releases).
   Não use cópias de terceiros.
2. Confira o SHA-256 do arquivo baixado. No PowerShell:

   ```powershell
   Get-FileHash .\Recomeco-0.1.0-x64.msi -Algorithm SHA256
   ```

   O resultado deve ser igual ao valor em `SHA256SUMS.txt`, na mesma release.
3. Se o SHA-256 não conferir ou se o Microsoft Defender detectar uma ameaça, interrompa a instalação.
   Não desative o antivírus e não crie exceções para instalar o Recomeço.

## Assinatura de código

Enquanto a assinatura de código não estiver disponível, as releases indicadas como
**sem assinatura** mostram "Editor desconhecido" no Windows. Por isso, a conferência do
SHA-256 é obrigatória.

## Apoio

- Autoexclusão oficial de apostas: https://www.gov.br/pt-br/servicos/plataforma-centralizada-de-autoexclusao-apostas
- CVV (24 horas, ligação gratuita): 188 ou https://cvv.org.br/quero-conversar/

## Problemas

Relate problemas de instalação em [Issues](https://github.com/davidazevedo/recomeco-releases/issues).
Não envie dados pessoais.
