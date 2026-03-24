# 📱 Produtividade App — PWA

Aplicativo de produtividade com hábitos, tarefas e relatório mensal.
Funciona offline e pode ser instalado como app no celular.

---

## 🚀 Deploy no Vercel (mais rápido — grátis)

### Opção A — Via GitHub (recomendado)

1. Crie uma conta em https://github.com (se não tiver)
2. Crie um repositório novo (ex: `produtividade-app`)
3. Faça upload de todos estes arquivos
4. Acesse https://vercel.com → "New Project"
5. Conecte o repositório do GitHub
6. Clique em **Deploy** — pronto! ✅

### Opção B — Via Vercel CLI (terminal)

```bash
npm install -g vercel
cd produtividade-app
npm install
vercel
```

---

## 🌐 Deploy no Netlify (alternativa)

1. Acesse https://app.netlify.com
2. Arraste a pasta inteira do projeto para a área de deploy
   (após rodar `npm run build`, use a pasta `dist/`)
3. Netlify gera um link automático ✅

Ou via CLI:
```bash
npm install -g netlify-cli
npm run build
netlify deploy --prod --dir=dist
```

---

## 💻 Rodar localmente

```bash
npm install
npm run dev
```
Acesse: http://localhost:5173

Para build de produção:
```bash
npm run build
npm run preview
```

---

## 📲 Instalar como app no celular

**Android (Chrome):**
1. Abra o link no Chrome
2. Toque nos 3 pontinhos (⋮) → "Adicionar à tela inicial"
3. Confirme ✅

**iPhone (Safari):**
1. Abra o link no Safari (obrigatório)
2. Toque no ícone de compartilhar (□↑)
3. Role e toque em "Adicionar à Tela de Início"
4. Confirme ✅

---

## 📁 Estrutura do projeto

```
produtividade-app/
├── public/
│   └── icons/
│       ├── icon-192.png
│       └── icon-512.png
├── src/
│   ├── App.jsx       ← App principal
│   └── main.jsx      ← Entry point
├── index.html
├── vite.config.js    ← Config PWA
├── package.json
└── README.md
```

---

## ✨ Funcionalidades

- ✅ Lista de tarefas com prioridade (alta / média / baixa)
- 🔄 Rastreamento de hábitos diários
- 📊 Progresso diário e semanal em tempo real
- 🗓️ Relatório mensal com mapa de calor
- 🔥 Contador de sequência (streak)
- 💾 Dados salvos localmente (funciona offline)
- 📱 Instalável como PWA no celular
