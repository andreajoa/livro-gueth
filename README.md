# 📚 Os Dois Iguais e o Segredo do Coração

Livro interativo online com navegação por páginas, miniaturas e suporte a toque/swipe.

## 🚀 Deploy no Vercel

### Opção 1 — Vercel CLI (recomendado)
```bash
npm i -g vercel
cd os-dois-iguais
vercel --prod
```

### Opção 2 — GitHub + Vercel (automático)
1. Crie um repositório no GitHub e faça push desta pasta
2. Acesse [vercel.com](https://vercel.com) → **Add New Project**
3. Importe o repositório
4. Clique em **Deploy** (sem nenhuma configuração — é tudo estático)

## 🐙 Push no GitHub
```bash
git init
git add .
git commit -m "feat: livro interativo Os Dois Iguais"
git remote add origin https://github.com/SEU_USUARIO/os-dois-iguais.git
git push -u origin main
```

## 📂 Estrutura
```
/
├── index.html       ← viewer do livro
├── vercel.json      ← config de deploy
├── .gitignore
├── README.md
└── images/
    ├── capa.png
    ├── page_02.jpg
    ├── page_03.jpg
    │   ...
    └── page_36.jpg
```

## ✨ Funcionalidades
- Navegação com botões ← →
- Teclado: setas esquerda/direita
- Swipe / arraste no celular
- Miniaturas clicáveis
- Barra de progresso
- Cache de imagens para carregamento rápido

---
*Texto: Margareth Almeida · Ilustrações: Tony Matos*
