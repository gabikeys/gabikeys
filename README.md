# Oi, eu sou o Gabi 👋

Desenvolvedor fullstack (Python + React) e professor de Matemática, Física e Química em Salvador/BA.

Crio e mantenho o **[Turmia](https://turmia.com.br)**, um SaaS com IA que gera material didático para professores e que está em uso numa escola real. Antes da sala de aula, estagiei em **Python na JusBrasil**, montando pipelines de dados jurídicos.

Gosto de resolver problemas que eu mesmo vivo: o Turmia nasceu das horas que eu passava preparando prova e apostila.

📫 **gabiteclas@gmail.com**

---

## 🚀 Projeto principal: [Turmia](https://turmia.com.br)

Plataforma em que o professor escolhe disciplina, série e tema, e a IA entrega o material pronto: apostila em PDF (LaTeX), slides com fórmulas, plano de aula alinhado à BNCC, correção de redação nas 5 competências do ENEM e correção de gabarito por foto.

- **Stack:** React + Vite · FastAPI · Supabase (Postgres, Auth e RLS) · Gemini · LaTeX · Docker · GitHub Actions
- **Em produção** com domínio próprio, planos pagos por professor e por escola, e um piloto na escola onde dou aula
- **Desafios que resolvi:**
  - políticas de **RLS** no Supabase pra isolar os dados de cada escola
  - limpeza do **LaTeX gerado pela IA**, que vem com vícios de formatação que quebram a compilação
  - **migração de Streamlit para React + FastAPI** com o app em uso
  - **testes com pytest**, simulando o Supabase e o Gemini, rodando no CI

*O código é privado, por ser um produto comercial.*

## 🛠️ Outros projetos

| Projeto | O que é | Stack |
|---|---|---|
| [loja-joaninha](https://github.com/gabikeys/loja-joaninha) | Site de pedidos estilo iFood para uma loja real de produtos de limpeza, com painel em que a dona cadastra os produtos pelo celular | Next.js · Supabase · Resend |
| [Azevedo Lopes Advocacia](https://azevedolopesadvocacia.com.br) | Site institucional para um escritório de advocacia real, com domínio próprio, SEO (Open Graph, dados estruturados) e versão pra celular | HTML · CSS · JavaScript · Vercel |
| [gymstats](https://github.com/gabikeys/gymstats) | Acompanhamento de treinos que diz se é hora de subir a carga (progressão dupla) | Next.js · TypeScript · Prisma · PostgreSQL |
| [baixador-videos](https://github.com/gabikeys/baixador-videos) | Baixa vídeos do Instagram, X e YouTube | Python · Flask · yt-dlp · Docker |
| [luanzzo-fitness](https://github.com/gabikeys/luanzzo-fitness) | Landing page de vendas para uma marca real, com conversão pelo WhatsApp | HTML · CSS · JavaScript |

## 🧰 Stack

**Backend:** Python · FastAPI · Flask · PostgreSQL · Supabase · Prisma
**Frontend:** React · Next.js · TypeScript · JavaScript · Tailwind
**IA:** Gemini API · engenharia de prompt · saída estruturada em JSON
**Infra:** Docker · GitHub Actions · Vercel · Render
**Testes:** pytest
