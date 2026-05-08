# 5º BPRv — Portal de Aplicações

Portal centralizado de links para os sistemas internos do 5º Batalhão de Polícia Rodoviária.

Identidade visual: https://guardian-sudeste-branding.lovable.app/

## Imagens necessárias

Adicionar na raiz do projeto antes do deploy:

| Arquivo | Uso |
|---------|-----|
| `asa_rodoviaria.png` | Logo asas — esquerda do header |
| `logo_5rv.png` | Escudo 5º BPRv — direita do header |
| `logo_coin2.png` | Medallion central — emblema do header |

## Deploy via Vercel CLI

```bash
# Instalar CLI (uma vez)
npm install -g vercel

# Login
vercel login

# Deploy produção
vercel --prod
```

## Deploy automático (GitHub → Vercel)

Todo `git push` na branch `main` dispara deploy automático quando o webhook estiver configurado.

```bash
git add .
git commit -m "descrição da mudança"
git push
```

## Aplicações vinculadas

| Sistema | URL |
|---------|-----|
| Controle de COPs | Apps Script |
| Controle de Prazos | Apps Script |
| Agendamentos | Apps Script |
| Check List Viaturas | Apps Script |

## URL de produção

https://frontendaplicacoes5bprvvercel.vercel.app
