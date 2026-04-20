# PLANO DO PROJETO: SK-Code-Editor-APK (5)

> Gerado automaticamente pelo SK Code Editor em 20/04/2026, 01:29:15
> **117 arquivo(s)** | **~27.200 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React + Vite, TypeScript, Tailwind CSS
- **Versao:** 0.0.0

**Para rodar o projeto:**
```bash
npm install && npm run dev
```

---

## ESTRUTURA DE ARQUIVOS

```
SK-Code-Editor-APK (5)/
├──  db/
│   └── neon.js/
│       ├── .gitkeep
│       └── neon.js
├── .replit-artifact/
│   └── artifact.toml
├── dist/
│   ├── assets/
│   │   ├── index-0VwVJX8N.js
│   │   └── index-Cnm3706z.css
│   ├── favicon.svg
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── index.html
│   ├── manifest.json
│   ├── opengraph.jpg
│   └── sw.js
├── neon/
│   ├── .gitkeep
│   └── .js
├── public/
│   ├── favicon.svg
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── manifest.json
│   ├── opengraph.jpg
│   └── sw.js
├── src/
│   ├── components/
│   │   ├── ui/
│   │   │   ├── accordion.tsx
│   │   │   ├── alert-dialog.tsx
│   │   │   ├── alert.tsx
│   │   │   ├── aspect-ratio.tsx
│   │   │   ├── avatar.tsx
│   │   │   ├── badge.tsx
│   │   │   ├── breadcrumb.tsx
│   │   │   ├── button-group.tsx
│   │   │   ├── button.tsx
│   │   │   ├── calendar.tsx
│   │   │   ├── card.tsx
│   │   │   ├── carousel.tsx
│   │   │   ├── chart.tsx
│   │   │   ├── checkbox.tsx
│   │   │   ├── collapsible.tsx
│   │   │   ├── command.tsx
│   │   │   ├── context-menu.tsx
│   │   │   ├── dialog.tsx
│   │   │   ├── drawer.tsx
│   │   │   ├── dropdown-menu.tsx
│   │   │   ├── empty.tsx
│   │   │   ├── field.tsx
│   │   │   ├── form.tsx
│   │   │   ├── hover-card.tsx
│   │   │   ├── input-group.tsx
│   │   │   ├── input-otp.tsx
│   │   │   ├── input.tsx
│   │   │   ├── item.tsx
│   │   │   ├── kbd.tsx
│   │   │   ├── label.tsx
│   │   │   ├── menubar.tsx
│   │   │   ├── navigation-menu.tsx
│   │   │   ├── pagination.tsx
│   │   │   ├── popover.tsx
│   │   │   ├── progress.tsx
│   │   │   ├── radio-group.tsx
│   │   │   ├── resizable.tsx
│   │   │   ├── scroll-area.tsx
│   │   │   ├── select.tsx
│   │   │   ├── separator.tsx
│   │   │   ├── sheet.tsx
│   │   │   ├── sidebar.tsx
│   │   │   ├── skeleton.tsx
│   │   │   ├── slider.tsx
│   │   │   ├── sonner.tsx
│   │   │   ├── spinner.tsx
│   │   │   ├── switch.tsx
│   │   │   ├── table.tsx
│   │   │   ├── tabs.tsx
│   │   │   ├── textarea.tsx
│   │   │   ├── toast.tsx
│   │   │   ├── toaster.tsx
│   │   │   ├── toggle-group.tsx
│   │   │   ├── toggle.tsx
│   │   │   └── tooltip.tsx
│   │   ├── AIChat.tsx
│   │   ├── AssistenteJuridico.tsx
│   │   ├── CampoLivre.tsx
│   │   ├── CodeEditor.tsx
│   │   ├── DriveBackupPanel.tsx
│   │   ├── EditorLayout.tsx
│   │   ├── FileTree.tsx
│   │   ├── GitHubPanel.tsx
│   │   ├── PackageSearch.tsx
│   │   ├── Preview.tsx
│   │   ├── QuickPrompt.tsx
│   │   ├── RealTerminal.tsx
│   │   ├── StreamTerminal.tsx
│   │   ├── TemplateSelector.tsx
│   │   ├── Terminal.tsx
│   │   ├── VoiceCard.tsx
│   │   └── VoiceMode.tsx
│   ├── hooks/
│   │   ├── use-mobile.tsx
│   │   └── use-toast.ts
│   ├── lib/
│   │   ├── ai-service.ts
│   │   ├── github-service.ts
│   │   ├── projects.ts
│   │   ├── store.ts
│   │   ├── templates.ts
│   │   ├── tts-service.ts
│   │   ├── utils.ts
│   │   ├── virtual-fs.ts
│   │   └── zip-service.ts
│   ├── pages/
│   │   └── not-found.tsx
│   ├── actions.ts
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── .env
├── capacitor.config.ts
├── components.json
├── index.html
├── MANUAL-APK.md
├── package.json
├── tsconfig.json
├── vite.config.apk.ts
└── vite.config.ts
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React + Vite, TypeScript, Tailwind CSS
- **Todos os pacotes (78):** @capacitor/core, @isomorphic-git/lightning-fs, @monaco-editor/react, @xterm/addon-fit, @xterm/addon-web-links, @xterm/xterm, file-saver, highlight.js, jszip, react-markdown, rehype-highlight, remark-gfm, @capacitor/android, @capacitor/cli, @hookform/resolvers, @radix-ui/react-accordion, @radix-ui/react-alert-dialog, @radix-ui/react-aspect-ratio, @radix-ui/react-avatar, @radix-ui/react-checkbox, @radix-ui/react-collapsible, @radix-ui/react-context-menu, @radix-ui/react-dialog, @radix-ui/react-dropdown-menu, @radix-ui/react-hover-card, @radix-ui/react-label, @radix-ui/react-menubar, @radix-ui/react-navigation-menu, @radix-ui/react-popover, @radix-ui/react-progress, @radix-ui/react-radio-group, @radix-ui/react-scroll-area, @radix-ui/react-select, @radix-ui/react-separator, @radix-ui/react-slider, @radix-ui/react-slot, @radix-ui/react-switch, @radix-ui/react-tabs, @radix-ui/react-toast, @radix-ui/react-toggle, @radix-ui/react-toggle-group, @radix-ui/react-tooltip, @replit/vite-plugin-cartographer, @replit/vite-plugin-dev-banner, @replit/vite-plugin-runtime-error-modal, @tailwindcss/typography, @tailwindcss/vite, @tanstack/react-query, @types/file-saver, @types/node, @types/react, @types/react-dom, @vitejs/plugin-react, @workspace/api-client-react, class-variance-authority, clsx, cmdk, date-fns, embla-carousel-react, framer-motion, input-otp, lucide-react, next-themes, react, react-day-picker, react-dom, react-hook-form, react-icons, react-resizable-panels, recharts, sonner, tailwind-merge, tailwindcss, tw-animate-css, vaul, vite, wouter, zod

---

## ROTAS DA API (endpoints detectados automaticamente)

```
GET    /api/items  (em dist/assets/index-0VwVJX8N.js)
GET    /api/items/:id  (em dist/assets/index-0VwVJX8N.js)
POST   /api/items  (em dist/assets/index-0VwVJX8N.js)
GET    /api/health  (em dist/assets/index-0VwVJX8N.js)
USE    /api/auth  (em dist/assets/index-0VwVJX8N.js)
USE    /api/usuarios  (em dist/assets/index-0VwVJX8N.js)
POST   /register  (em dist/assets/index-0VwVJX8N.js)
POST   /login  (em dist/assets/index-0VwVJX8N.js)
GET    /perfil  (em dist/assets/index-0VwVJX8N.js)
GET    /api/items  (em src/lib/templates.ts)
GET    /api/items/:id  (em src/lib/templates.ts)
POST   /api/items  (em src/lib/templates.ts)
GET    /api/health  (em src/lib/templates.ts)
USE    /api/auth  (em src/lib/templates.ts)
USE    /api/usuarios  (em src/lib/templates.ts)
POST   /register  (em src/lib/templates.ts)
POST   /login  (em src/lib/templates.ts)
GET    /perfil  (em src/lib/templates.ts)
```

---

## SCRIPTS DISPONIVEIS (package.json)

```bash
npm run dev           # vite --config vite.config.ts --host 0.0.0.0
npm run build         # vite build --config vite.config.ts
npm run serve         # vite preview --config vite.config.ts --host 0.0.0.0
npm run typecheck     # tsc -p tsconfig.json --noEmit
npm run build:web     # vite build --config vite.config.apk.ts
npm run cap:init      # npx cap init "SK Code Editor" com.skcodeeditor.app --web-dir dist
npm run cap:add:android  # npx cap add android
npm run cap:sync      # npx cap sync android
npm run cap:open      # npx cap open android
npm run build:apk     # npm run build:web && npx cap sync android
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
DATABASE_URL=seu_valor_aqui
PORT=seu_valor_aqui
ALLOWED_ORIGINS=seu_valor_aqui
JWT_SECRET=seu_valor_aqui
JWT_EXPIRES_IN=seu_valor_aqui
BASE_PATH=seu_valor_aqui
REPL_ID=seu_valor_aqui
NODE_ENV=seu_valor_aqui
SESSION_SECRET=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `dist/index.html` — Arquivo principal
- `index.html` — Pagina HTML principal
- `src/App.tsx` — Componente raiz do frontend
- `src/main.tsx` — Arquivo principal

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`.env`** _(5 linhas)_
Arquivo de variaveis secretas (senhas, chaves de API). NUNCA suba este arquivo para o GitHub.

**`MANUAL-APK.md`** _(655 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`capacitor.config.ts`** _(24 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(36 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(101 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(23 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.apk.ts`** _(21 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`vite.config.ts`** _(76 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `dist/`
> Codigo compilado/gerado automaticamente — NAO edite diretamente.

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(32 linhas)_
Arquivo de imagem.

**`icon-512.png`** _(100 linhas)_
Arquivo de imagem.

**`index.html`** _(37 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(49 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(17 linhas)_
Arquivo de imagem.

**`sw.js`** _(41 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `neon/`
> Pasta 'neon' — agrupamento de arquivos relacionados.

**`.gitkeep`** _(1 linha)_
Arquivo GITKEEP — parte do projeto.

**`.js`** _(398 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(32 linhas)_
Arquivo de imagem.

**`icon-512.png`** _(100 linhas)_
Arquivo de imagem.

**`manifest.json`** _(49 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(17 linhas)_
Arquivo de imagem.

**`sw.js`** _(41 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(210 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`actions.ts`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.css`** _(269 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 ` db/neon.js/`
> Pasta 'neon.js' — agrupamento de arquivos relacionados.

**`.gitkeep`** _(1 linha)_
Arquivo GITKEEP — parte do projeto.

**`neon.js`** _(32 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `dist/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`index-0VwVJX8N.js`** _(2702 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-Cnm3706z.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

---

### 📁 `src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(2226 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`AssistenteJuridico.tsx`** _(1190 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CampoLivre.tsx`** _(499 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CodeEditor.tsx`** _(154 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`DriveBackupPanel.tsx`** _(200 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`EditorLayout.tsx`** _(2520 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`FileTree.tsx`** _(400 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubPanel.tsx`** _(632 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`PackageSearch.tsx`** _(415 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`Preview.tsx`** _(496 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`QuickPrompt.tsx`** _(274 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`RealTerminal.tsx`** _(625 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`StreamTerminal.tsx`** _(495 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TemplateSelector.tsx`** _(501 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1516 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VoiceCard.tsx`** _(427 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`VoiceMode.tsx`** _(277 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`ai-service.ts`** _(392 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`github-service.ts`** _(197 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`projects.ts`** _(206 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`store.ts`** _(38 linhas)_
STORE de estado — gerencia o estado global do app (dados compartilhados entre telas).

**`templates.ts`** _(1629 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts-service.ts`** _(294 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`virtual-fs.ts`** _(200 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zip-service.ts`** _(163 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`not-found.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: SK-Code-Editor-APK (5)
Tipo: Aplicacao Web Frontend (React)
Stack: React + Vite, TypeScript, Tailwind CSS
Arquivos: 117 | Linhas: ~27.200
Rotas API: 18 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: DATABASE_URL, PORT, ALLOWED_ORIGINS, JWT_SECRET, JWT_EXPIRES_IN, BASE_PATH, REPL_ID, NODE_ENV, SESSION_SECRET

Estrutura principal:
   db/neon.js/.gitkeep
   db/neon.js/neon.js
  .env
  .replit-artifact/artifact.toml
  MANUAL-APK.md
  capacitor.config.ts
  components.json
  dist/assets/index-0VwVJX8N.js
  dist/assets/index-Cnm3706z.css
  dist/favicon.svg
  dist/icon-192.png
  dist/icon-512.png
  dist/index.html
  dist/manifest.json
  dist/opengraph.jpg
  dist/sw.js
  index.html
  neon/.gitkeep
  neon/.js
  package.json
  public/favicon.svg
  public/icon-192.png
  public/icon-512.png
  public/manifest.json
  public/opengraph.jpg
  public/sw.js
  src/App.tsx
  src/actions.ts
  src/components/AIChat.tsx
  src/components/AssistenteJuridico.tsx
  src/components/CampoLivre.tsx
  src/components/CodeEditor.tsx
  src/components/DriveBackupPanel.tsx
  src/components/EditorLayout.tsx
  src/components/FileTree.tsx
  src/components/GitHubPanel.tsx
  src/components/PackageSearch.tsx
  src/components/Preview.tsx
  src/components/QuickPrompt.tsx
  src/components/RealTerminal.tsx
  src/components/StreamTerminal.tsx
  src/components/TemplateSelector.tsx
  src/components/Terminal.tsx
  src/components/VoiceCard.tsx
  src/components/VoiceMode.tsx
  src/components/ui/accordion.tsx
  src/components/ui/alert-dialog.tsx
  src/components/ui/alert.tsx
  src/components/ui/aspect-ratio.tsx
  src/components/ui/avatar.tsx
  src/components/ui/badge.tsx
  src/components/ui/breadcrumb.tsx
  src/components/ui/button-group.tsx
  src/components/ui/button.tsx
  src/components/ui/calendar.tsx
  src/components/ui/card.tsx
  src/components/ui/carousel.tsx
  src/components/ui/chart.tsx
  src/components/ui/checkbox.tsx
  src/components/ui/collapsible.tsx
  src/components/ui/command.tsx
  src/components/ui/context-menu.tsx
  src/components/ui/dialog.tsx
  src/components/ui/drawer.tsx
  src/components/ui/dropdown-menu.tsx
  src/components/ui/empty.tsx
  src/components/ui/field.tsx
  src/components/ui/form.tsx
  src/components/ui/hover-card.tsx
  src/components/ui/input-group.tsx
  src/components/ui/input-otp.tsx
  src/components/ui/input.tsx
  src/components/ui/item.tsx
  src/components/ui/kbd.tsx
  src/components/ui/label.tsx
  src/components/ui/menubar.tsx
  src/components/ui/navigation-menu.tsx
  src/components/ui/pagination.tsx
  src/components/ui/popover.tsx
  src/components/ui/progress.tsx
  src/components/ui/radio-group.tsx
  src/components/ui/resizable.tsx
  src/components/ui/scroll-area.tsx
  src/components/ui/select.tsx
  src/components/ui/separator.tsx
  src/components/ui/sheet.tsx
  src/components/ui/sidebar.tsx
  src/components/ui/skeleton.tsx
  src/components/ui/slider.tsx
  src/components/ui/sonner.tsx
  src/components/ui/spinner.tsx
  src/components/ui/switch.tsx
  src/components/ui/table.tsx
  src/components/ui/tabs.tsx
  src/components/ui/textarea.tsx
  src/components/ui/toast.tsx
  src/components/ui/toaster.tsx
  src/components/ui/toggle-group.tsx
  src/components/ui/toggle.tsx
  src/components/ui/tooltip.tsx
  src/hooks/use-mobile.tsx
  src/hooks/use-toast.ts
  src/index.css
  src/lib/ai-service.ts
  src/lib/github-service.ts
  src/lib/projects.ts
  src/lib/store.ts
  src/lib/templates.ts
  src/lib/tts-service.ts
  src/lib/utils.ts
  src/lib/virtual-fs.ts
  src/lib/zip-service.ts
  src/main.tsx
  src/pages/not-found.tsx
  tsconfig.json
  vite.config.apk.ts
  vite.config.ts
```

---

*Plano gerado pelo SK Code Editor — 20/04/2026, 01:29:15*