# Tucumã PDF — versões

O Editor de PDF da **Câmara Municipal de Parintins**: leitor, editor, assinador e scan num único aplicativo.

Este repositório guarda só as **versões publicadas** (instaladores e arquivos de atualização). O
código-fonte fica num repositório privado da Câmara.

## Instalar

1. Abra a [versão mais recente](https://github.com/altairtb/tucuma-pdf-versoes/releases/latest) e
   baixe `TucumaPDF_<versão>_x64-setup.exe`.
2. Execute o instalador. Ele instala só para o usuário atual, sem pedir senha de administrador.
3. Para abrir PDFs com duplo clique: botão direito num PDF → **Abrir com** → **Escolher outro
   aplicativo** → **Tucumã PDF** → **Sempre**.

Requisitos: Windows 10 ou 11, 64 bits.

## Atualizar

No programa, aba **Arquivo** → **Verificar atualizações**: a versão nova é baixada e instalada com
um clique, sem desinstalar nada. O setor de informática pode atualizar sem interação com
`cmpin.exe --atualizar`.

As atualizações são assinadas digitalmente: o programa só instala arquivos com a assinatura do
projeto. O arquivo `latest.json` de cada versão é o que o botão de atualização consulta.
