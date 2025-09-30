
# Toolkit de Caminhos Financeiros — Moçambique (React + Vite + Tailwind)

Versão pronta para publicar no Netlify. Conteúdo em **Português**, com alternância para **EN**.

## ✅ O que vem incluído
- Mapa de decisão interativo
- Calculadora de orçamento (com download de CSV)
- Comparador de empréstimos
- Layout móvel-first com TailwindCSS
- `netlify.toml` configurado (build e pasta `dist`)

---

## 🚀 Como publicar (sem programar)
1) **Subir para o GitHub**
- Crie um repositório público (ex.: `financial-pathways-mz`).
- No GitHub, clique em **Add file → Upload files** e carregue todos os ficheiros desta pasta.
- Clique **Commit changes**.

2) **Conectar no Netlify**
- Entre em https://app.netlify.com/
- **Add new site → Import an existing project**
- Escolha **GitHub** e selecione o repositório.
- Build command: `npm run build`
- Publish directory: `dist`
- Clique **Deploy Site**

✅ Em poucos minutos terá um link público.

---

## 🛠️ Como editar textos (sem programar)
- Abra `src/App.jsx` e edite os textos em português (procure pelas strings dentro de `t('PT','EN')`).
- Faça commit no GitHub → o Netlify publica automaticamente.

---

## 💻 Rodar localmente (opcional)
- Instale Node LTS (18+).
- `npm install`
- `npm run dev` (abre em http://localhost:5173)

---

## 📁 Estrutura
- `index.html`: página base
- `src/App.jsx`: conteúdo principal e componentes
- `src/main.jsx`: inicialização React
- `src/styles/index.css`: Tailwind
- `tailwind.config.js` e `postcss.config.js`: configs do Tailwind
- `netlify.toml`: configuração de build/`dist`

---

Feito para iDE Moçambique. Qualquer dúvida, edite `App.jsx` ou abra um issue no GitHub.
