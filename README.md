# Portfólio Profissional — Tiago Boaventura Amaral

**Disciplina:** Laboratório de Desenvolvimento de Software (João Aramuni)  
**Alunos:** Kayque Allan e Tiago Boaventura Amaral

Portfólio Profissional
Neste laboratório, vamos projetar e desenvolver um website do seu portfólio
profissional. Leia atentamente a descrição fornecida pelo Product Owner e elabore o
projeto detalhado do sistema, incluindo front-end, back-end e hospedagem na nuvem.
Descrição do Sistema:
O objetivo é desenvolver um website de portfólio profissional para você, que deseja
apresentar sua trajetória, habilidades, projetos e formas de contato de maneira moderna
e acessível. O sistema deverá conter as seguintes seções acessadas por um menu de
navegação:
1. Sobre Mim
• Breve apresentação em português e inglês, destacando sua formação, área de
atuação, interesses e objetivos profissionais.
2. Projetos
• Seção com linha do tempo de projetos, do mais antigo ao mais recente.
• Cada projeto deverá conter:
o Nome e descrição;
o Tecnologias utilizadas;
o Link para o repositório no GitHub;
o Imagem ou GIF com o projeto em funcionamento (telas, login,
interações).
3. Experiências
• Espaço para relatar experiências profissionais, estágios, freelas, participações em
projetos open source ou eventos técnicos.
• Para cada item: nome da empresa/instituição, cargo ou atividade, período e breve
descrição.
2
4. Contato
• Página com: Ícones clicáveis para e-mail, WhatsApp, LinkedIn, entre outros;
• Formulário com campos de nome, e-mail e mensagem, com funcionalidade de
envio por e-mail.
O sistema deve ter um design responsivo, interface amigável e identidade visual
coerente com seu perfil profissional. Ao final, o site deverá estar hospedado
gratuitamente em nuvem (ex: Render, Vercel, Heroku, Fly.io), e o repositório no
GitHub deverá conter um README completo, incluindo:
• Listagem das tecnologias utilizadas;
• Relação das dependências e bibliotecas/frameworks usados;
• Estrutura de diretórios do projeto;
• Instruções de instalação e execução do sistema localmente;
• Link de acesso para o site publicado na nuvem.


## 🧱 Tecnologias previstas

- **React 18** + **Vite 5**
- **React Router** para navegação
- **CSS Modules** para estilos
- (Futuro) **EmailJS** para formulário de contato
- (Futuro) Hospedagem em **Vercel**

## 📦 Estrutura de diretórios (inicial)

```
.
├─ public/
├─ src/
│  ├─ assets/
│  ├─ components/
│  ├─ pages/
│  │  ├─ Contato.jsx
│  │  ├─ Experiencias.jsx
│  │  ├─ Home.jsx
│  │  ├─ Projetos.jsx
│  │  └─ SobreMim.jsx
│  ├─ styles/
│  │  ├─ AppLayout.module.css
│  │  └─ global.css
│  ├─ App.jsx
│  └─ main.jsx
├─ .gitignore
├─ index.html
├─ package.json
├─ vite.config.js
└─ README.md
```

## ▶️ Como rodar localmente

> Pré-requisitos: Node.js 18+ e npm/pnpm/yarn.

```bash
# instalar dependências
npm install

# ambiente de desenvolvimento
npm run dev # Runs on http://localhost:5174/ (or 5175 if 5174 is in use)

# build de produção
npm run build

# preview do build
npm run preview
```

---



