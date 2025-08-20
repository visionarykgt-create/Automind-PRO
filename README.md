# 🚗 Automind PRO

**Automind PRO** é um micro-SaaS automotivo completo para concessionárias, revendedoras e lojistas de veículos.  
Inspirado em plataformas como o AutoCerto, ele permite gerenciar anúncios, leads e vendas de forma simples e eficiente.  

## ✨ Funcionalidades
- Cadastro de veículos com fotos e descrição
- Site da loja totalmente responsivo (mobile/tablet/desktop)
- Integração com WhatsApp/Zaia para atendimento automático
- Gerenciador de leads e CRM integrado
- Avaliação de veículos pela Tabela FIPE
- Painel de administração em **tema escuro**
- Emissão de relatórios e gestão financeira

## 🛠️ Tecnologias utilizadas
- [Next.js](https://nextjs.org/) + [Supabase](https://supabase.com/) + [Vercel](https://vercel.com/)  
*(ou Blazor Server + Azure, caso use stack .NET)*

## 🚀 Como rodar localmente
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/automind-pro.git
   cd automind-pro
   npm install
NEXT_PUBLIC_SUPABASE_URL=xxxx
NEXT_PUBLIC_SUPABASE_ANON_KEY=xxxx
npm run dev

