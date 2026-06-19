# 🧠 Fisioterapia Neuropediátrica — Guia de Estudo

Site de estudo (página única) com resumo da disciplina de Fisioterapia Neuropediátrica: CIF e neuroplasticidade, Paralisia Cerebral (definição, classificação, diagnóstico precoce e intervenção), AME, Distrofias Musculares, Mielomeningocele, Síndrome de Down e um resumo das escalas de avaliação. Inclui **pesquisa no conteúdo**, **flashcards** e **quiz** de revisão.

Site estático, sem dependências — basta abrir o `index.html`.

---

## 🚀 Como colocar online no Vercel

### Opção A — Pelo site do Vercel (sem comandos)

1. Crie conta em **https://vercel.com** (pode entrar com o GitHub).
2. **Add New → Project** e conecte/importe o repositório do GitHub (veja abaixo).
3. O Vercel detecta site estático automaticamente — clique em **Deploy**.
4. Em segundos fica no ar num endereço tipo `https://neuropediatria.vercel.app`.

### Opção B — Vercel CLI

```bash
npm install -g vercel
cd neuropediatria
vercel
vercel --prod
```

---

## 📦 Como subir no GitHub

Dentro da pasta `neuropediatria`:

```bash
git init
git add .
git commit -m "Site de estudo de Fisioterapia Neuropediátrica"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/neuropediatria.git
git push -u origin main
```

> Crie antes um repositório **vazio** em https://github.com/new chamado `neuropediatria`.

A cada `git push`, o site no Vercel atualiza sozinho. ✨

---

## 📁 Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | O site inteiro (conteúdo, estilo e scripts) |
| `vercel.json` | Configuração de hospedagem |
| `.gitignore` | Arquivos ignorados pelo Git |
| `README.md` | Este guia |

---

Conteúdo baseado nas aulas da Prof.ª Dra. Eloá Chiquetti e materiais complementares. Bons estudos! 🍀
