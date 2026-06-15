# Registro de Conversa — Grupo de WhatsApp

Este repositório hospeda o **registro do histórico de um grupo de WhatsApp** do qual fiz parte, mantido para fins de **registro pessoal**.

🔗 **Acesso:** https://vcapis.github.io/registro-grupo/

## 🔒 Conteúdo protegido por senha

O conteúdo está **criptografado com AES-256** dentro do próprio arquivo HTML (via [StatiCrypt](https://github.com/robinmoisson/staticrypt)). Ao abrir o link, a página pede uma senha e só descriptografa o conteúdo **no seu navegador**.

Mesmo sendo um repositório público, **nenhuma mensagem, nome ou número de telefone fica exposto** — sem a senha, vê-se apenas a tela de bloqueio.

> A senha **não** está neste repositório. Ela é compartilhada de forma privada apenas com quem tem autorização para acessar.

## 📄 Sobre o registro

- Gerado a partir da exportação oficial da conversa (recurso **"Exportar conversa"** do próprio WhatsApp).
- Reúne as mensagens de texto e as mídias (fotos, figurinhas, áudios, vídeos e documentos) disponíveis no momento do export.
- As **mídias estão embutidas** no próprio HTML (base64) — o arquivo é autossuficiente.
- A página oferece **filtros** (busca por texto, por participante, por tipo e por período) e botões para **imprimir/salvar em PDF** e **baixar uma cópia**.

## 🗂️ Estrutura

```
site/
  index.html              # página de acesso (conteúdo criptografado)
  registro_completo.html  # mesma versão criptografada
```

Os arquivos originais não criptografados (export `.zip`, `.txt`, CSV e mídias soltas) **não** fazem parte deste repositório, por conterem dados pessoais em claro.

## ⚠️ Privacidade

O registro contém dados pessoais de participantes do grupo (nomes e números). O acesso é restrito por senha justamente para preservar essa privacidade. Não redistribua o conteúdo nem a senha sem necessidade.
