# Filmes Studio AI - Agregador Legal de Filmes

Plataforma moderna de descoberta de filmes com inteligência artificial, usando dados legítimos do TMDB e streaming legal.

## ✨ Funcionalidades

- 🤖 **IA Inteligente** - Recomendações com Google Gemini
- 🔍 **Busca Avançada** - Por gênero, ator, ano
- 🎬 **Dados TMDB** - Informações oficiais de filmes
- 💬 **Chat AI** - Assistente de recomendações
- 📱 **Responsivo** - Funciona em qualquer dispositivo
- ⭐ **Avaliações** - Sistema de notas e comentários
- 🔐 **Seguro** - Autenticação com Firebase

## 🚀 Como Começar

### Requisitos
- Node.js 16+
- npm ou yarn
- Conta Google (para API Gemini)
- Conta TMDB (grátis)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/zuanelson717-cloud/site-copiado.git
cd site-copiado

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env.local
# Edite .env.local com suas chaves

# Inicie o servidor de desenvolvimento
npm run dev
```

## 📝 Configuração

1. **Google Gemini API**
   - Acesse: https://aistudio.google.com/app/apikey
   - Crie uma chave de API
   - Adicione em `.env.local`

2. **TMDB API** (Filmes)
   - Acesse: https://www.themoviedb.org/settings/api
   - Crie uma conta grátis
   - Gere sua chave de API
   - Adicione em `.env.local`

3. **Firebase** (Banco de dados)
   - Acesse: https://firebase.google.com/
   - Crie um novo projeto
   - Configure as credenciais
   - Adicione em `.env.local`

## 📦 Scripts

```bash
npm run dev          # Inicia em desenvolvimento
npm run build        # Build para produção
npm run preview      # Preview da build
npm run lint         # Verifica o código
```

## 🏗️ Estrutura do Projeto

```
src/
├── components/         # Componentes React
├── pages/             # Páginas da aplicação
├── services/          # Serviços (API, Firebase, etc)
├── utils/             # Funções utilitárias
├── styles/            # CSS/SCSS
├── types/             # TypeScript types
└── App.tsx            # Componente raiz
```

## 🔗 Links Úteis

- [TMDB API](https://www.themoviedb.org/settings/api)
- [Google Gemini](https://aistudio.google.com)
- [Firebase Console](https://console.firebase.google.com)
- [Vite Documentation](https://vitejs.dev)

## 📄 Licença

MIT - Veja LICENSE.md

## 👥 Contribuir

Contribuições são bem-vindas! Faça um fork e envie um pull request.

---

**Feito com ❤️ por zuanelson717-cloud**
