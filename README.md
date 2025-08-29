# ReUse Jovem ♻️

**Plataforma de troca e venda de roupas com foco em sustentabilidade e moda circular**

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-blue)](https://expressjs.com/)
[![License](https://img.shields.io/badge/License-ISC-yellow)](LICENSE)

## 📋 Sobre o Projeto

O **ReUse Jovem** é uma plataforma inovadora que conecta pessoas interessadas em trocar, vender e reutilizar roupas. Nosso objetivo é promover a sustentabilidade na moda, reduzir o desperdício têxtil e criar uma comunidade consciente sobre consumo responsável.

### 🎯 Público-Alvo
- Jovens interessados em moda sustentável
- Pessoas que buscam renovar o guarda-roupa sem consumir novas peças
- Entusiastas de economia circular e upcycling

## ✨ Funcionalidades Principais

### 🔄 Sistema de Trocas
- **Propostas de Troca**: Ofereça suas peças em troca de itens de outros usuários
- **Negociações**: Sistema completo de propostas, aceitação e recusa
- **Notificações**: Acompanhe suas negociações pendentes em tempo real

### 🛒 Venda de Peças
- **Cadastro de Produtos**: Adicione peças para venda com preços personalizados
- **Categorização**: Organize por gênero (Masculino, Feminino, Infantil) e tipo
- **Upload de Imagens**: Sistema de upload com validação e otimização

### 👤 Sistema de Usuários
- **Cadastro e Login**: Autenticação segura com sessões
- **Perfil Personalizável**: Upload de foto de perfil e informações pessoais
- **Gestão de Peças**: Visualize e gerencie todas as suas peças cadastradas

### 🤖 Chatbot Inteligente
- **Assistente de Moda**: Chatbot integrado com modelo LLaMA3 local
- **Dicas Personalizadas**: Receba sugestões de combinações e customização
- **Suporte 24/7**: Tire dúvidas sobre o funcionamento da plataforma

### 🎨 Interface Moderna
- **Design Responsivo**: Adaptado para desktop e mobile
- **Tema Claro/Escuro**: Modo notativo com transições suaves
- **Experiência Intuitiva**: Navegação simplificada e acessível

## 🛠️ Tecnologias Utilizadas

### Backend
- **Node.js** - Runtime JavaScript
- **Express.js** - Framework web
- **Multer** - Upload de arquivos
- **Express-session** - Gerenciamento de sessões
- **SQLite3** - Banco de dados (em memória para demonstração)
- **@xenova/transformers** - Modelo LLaMA3 local para chatbot

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilos customizados com variáveis CSS
- **Tailwind CSS** - Framework utilitário
- **JavaScript (ES6+)** - Interatividade e consumo de API
- **Font Awesome** - Ícones
- **Google Fonts (Poppins)** - Tipografia

### Ferramentas de Deploy
- **Render** - Hospedagem do backend
- **Railway** - Plataforma alternativa de deploy
- **Vercel** - Hospedagem do frontend

## 📁 Estrutura do Projeto

```
vivo1/
├── back/                    # Backend Node.js
│   ├── server.js           # Servidor principal
│   ├── package.json        # Dependências do backend
│   ├── uploads/            # Arquivos uploadados
│   └── *.js               # Scripts auxiliares e testes
├── front/                  # Frontend
│   ├── index.html         # Página inicial
│   ├── login.html         # Página de login
│   ├── cadastro.html      # Página de cadastro
│   ├── loja.html          # Loja de peças
│   ├── perfil.html        # Perfil do usuário
│   ├── negociacoes.html   # Gerenciamento de negociações
│   ├── styles.css         # Estilos globais
│   ├── script.js          # Scripts comuns
│   ├── theme.js           # Gerenciamento de tema
│   └── chatbot-package/   # Integração do chatbot
├── chatbot-package/       # Pacote independente do chatbot
│   ├── chatbot.js         # Lógica do chatbot
│   ├── chatbot.css        # Estilos do chatbot
│   └── README.md          # Documentação do chatbot
├── image/                 # Assets visuais
│   ├── logo.png          # Logo da plataforma
│   ├── banner.png        # Banner principal
│   └── *.jpg/png         # Imagens de exemplo
├── package.json          # Configuração principal
├── railway.json          # Configuração Railway
├── render.yaml           # Configuração Render
├── vercel.json           # Configuração Vercel
└── README.md            # Este arquivo
```

## 🚀 Como Executar Localmente

### Pré-requisitos
- Node.js 18+ instalado
- npm ou yarn

### Passo a Passo

1. **Clone o repositório**
   ```bash
   git clone https://github.com/bia7711/vivo1.git
   cd vivo1
   ```

2. **Instale as dependências do backend**
   ```bash
   cd back
   npm install
   ```

3. **Instale as dependências do frontend** (se necessário)
   ```bash
   cd ../front
   # As dependências são gerenciadas via CDN
   ```

4. **Execute o servidor**
   ```bash
   cd ../back
   npm start
   ```

5. **Acesse a aplicação**
   Abra seu navegador e vá para: `http://localhost:3000`

### Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm start` - Inicia o servidor de produção
- `npm run build` - Comando de build (para deploy)

## 🌐 Deploy

### Render (Backend)
O backend está configurado para deploy no Render. O arquivo `render.yaml` contém a configuração necessária.

### Vercel (Frontend)
O frontend pode ser deployado na Vercel usando o arquivo `vercel.json`.

### Railway
Configuração alternativa disponível no arquivo `railway.json`.

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Contato

- **Repositório**: [github.com/bia7711/vivo1](https://github.com/bia7711/vivo1)
- **Issues**: [Reportar problemas](https://github.com/bia7711/vivo1/issues)

## 📄 Licença

Este projeto está sob a licença ISC. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**ReUse Jovem** - Transformando a moda, uma troca de cada vez! ♻️✨

*Projeto desenvolvido com foco em sustentabilidade e tecnologia.*
