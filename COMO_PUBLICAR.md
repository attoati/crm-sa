# Como Publicar o CRM no GitHub Pages
## Acesso de qualquer lugar — iPad, celular, sem PC ligado

---

## O que você vai precisar

- Uma conta no GitHub (gratuita) — https://github.com
- Esta pasta: `CRM SANTO ANGELO CLOUD`

---

## PASSO 1 — Criar conta no GitHub

1. Acesse **https://github.com/signup**
2. Escolha um username (ex: `a2tsantoangelo`)
3. Confirme o e-mail
4. Selecione o plano **Free**

> Se já tem conta GitHub, pule para o Passo 2.

---

## PASSO 2 — Criar o repositório

1. Clique em **"New repository"** (botão verde no canto superior direito)
2. Preencha:
   - **Repository name:** `crm-sa` (ou qualquer nome sem espaço)
   - **Visibility:** `Public` ✅ (obrigatório para GitHub Pages gratuito)
   - **Add a README file:** deixe DESMARCADO
3. Clique **"Create repository"**

---

## PASSO 3 — Fazer upload dos arquivos

1. Na página do repositório recém-criado, clique em **"uploading an existing file"**
   (ou arraste para a área central da tela)
2. Selecione **TODOS** os arquivos da pasta `CRM SANTO ANGELO CLOUD`:
   - `CRM_SANTO_ANGELO.html`
   - `APRESENTACAO.html`
   - `CRM_DATA.json`
   - `Logo Santo Angelo - Preto Sem Fundo.png`
   - `index.html`
   - `manifest.json`
   - `.nojekyll` (arquivo oculto — ative "mostrar arquivos ocultos" no Windows)
3. Clique **"Commit changes"** (botão verde lá embaixo)

> Para ver arquivos ocultos no Windows: no Explorer, clique em "Ver" → marque "Itens ocultos"

---

## PASSO 4 — Ativar o GitHub Pages

1. No repositório, clique em **Settings** (engrenagem no topo)
2. No menu lateral esquerdo, clique em **Pages**
3. Em **"Branch"**, selecione `main` e clique **Save**
4. Aguarde 1-2 minutos

---

## PASSO 5 — Acessar o CRM

Após ativar, o GitHub mostrará a URL do seu CRM. Será algo como:

```
https://SEU_USERNAME.github.io/crm-sa/
```

Exemplo: `https://a2tsantoangelo.github.io/crm-sa/`

**Acesse essa URL no Safari do iPad** — funciona de qualquer lugar do mundo, sem PC ligado.

---

## Adicionar à tela inicial do iPad (recomendado)

1. Abra a URL no **Safari**
2. Toque no ícone de compartilhar (quadrado com seta para cima)
3. Toque em **"Adicionar à Tela de Início"**
4. Dê o nome **"CRM SA"** e confirme

O CRM aparecerá como um app na tela inicial, abrindo em tela cheia.

---

## Como atualizar os arquivos depois

Quando precisar atualizar (ex: nova lista de produtos):

1. Acesse o repositório no GitHub
2. Clique no arquivo que quer substituir (ex: `CRM_DATA.json`)
3. Clique no ícone de lápis (editar) ou **"..."** → **"Upload file"**
4. Faça o upload da versão nova
5. Clique **"Commit changes"**

A atualização aparece em 1-2 minutos automaticamente.

---

## Sobre os pedidos salvos

- Os pedidos ficam salvos no **iPad** (localStorage do Safari)
- Não são enviados para a internet — ficam só no dispositivo
- Se limpar os dados do Safari, os pedidos somem
- Para backup: use **"Exportar Pedidos"** dentro do CRM e salve o arquivo

---

## Dúvidas frequentes

**O CRM é público na internet?**
Sim — qualquer pessoa com a URL pode acessar. Mas a URL é aleatória e não aparece em buscas. Para uso interno, é seguro o suficiente.

**Posso usar outro dispositivo além do iPad?**
Sim — funciona em qualquer navegador moderno (Chrome, Safari, Firefox).

**O CRM funciona sem internet no iPad?**
Não — precisa de conexão para carregar a página. Mas uma vez carregada, funciona offline por alguns minutos.

**E os dados dos clientes e produtos?**
Ficam no `CRM_DATA.json` hospedado no GitHub. Apenas quem tem o link pode ver.
