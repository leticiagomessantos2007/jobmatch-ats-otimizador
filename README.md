# 📄 JobMatch ATS - Otimizador de Currículos Inteligente

> Aplicação Web desenvolvida com **Lovable** para comparar currículos com descrições de vagas e gerar versões otimizadas para sistemas **ATS (Applicant Tracking Systems)**.

👉 **Aplicação Publicada:** [https://jobmatch-ats-otimizador.lovable.app](https://jobmatch-ats-otimizador.lovable.app)

---

## 🎯 1. O Problema Resolvido
Milhares de candidatos qualificados têm seus currículos descartados automaticamente por robôs de leitura de RH (os chamados **ATS** - *Applicant Tracking Systems*) antes mesmo de serem lidos por um recrutador humano. Isso acontece pela ausência de palavras-chave estratégicas e formatações inadequadas.

O **JobMatch ATS** resolve essa dor ao comparar em tempo real o currículo do candidato com a descrição da vaga desejada, destacando lacunas e gerando uma versão ATS-friendly pronta para envio.

> ⚠️ **Regra Fundamental de Ética:** A aplicação aperfeiçoa a apresentação das experiências e destaca competências reais, **nunca inventando ou criando experiências falsas**.

---

## 🤖 2. Mega Prompt Utilizado

```markdown
# Contexto e Objetivo
Atue como um Engenheiro de Software especialista em UX/UI e Sistemas de Recrutamento (ATS). Crie uma aplicação Web chamada "JobMatch ATS" que ajuda candidatos a otimizarem seus currículos para vagas de emprego.

# Arquitetura e Telas
1. **Header / Navbar:**
   - Logo da aplicação "JobMatch ATS".
   - Tagline: "Aumente suas chances de passar pelo filtro dos recrutadores".

2. **Área Principal de Entrada (Side-by-Side):**
   - Lado Esquerdo: Campo de texto (Textarea) para colar a **Descrição da Vaga**.
   - Lado Direito: Campo de texto (Textarea) para colar o **Currículo Atual**.
   - Botão Central de Ação: "Analisar e Otimizar Currículo" com ícone de brilho (Sparkles).

3. **Painel de Resultados (Dashboard de Match):**
   - **Match Score:** Card em destaque com a porcentagem de compatibilidade (0 a 100%).
   - **Palavras-chave Encontradas:** Tags em Verde com as competências identificadas.
   - **Palavras-chave Faltantes:** Tags em Vermelho/Laranja com termos cruciais que faltam no currículo.
   - **Gaps de Formatação:** Dicas de melhoria estrutural (seções, cargos, datas).

4. **Gerador de Currículo ATS-Friendly:**
   - Pré-visualização do currículo reformatado e otimizado com as palavras-chave integradas de forma natural.
   - Botões de exportação: "Baixar em PDF" e "Copiar Texto".

# Design System e Estilo
- **Biblioteca:** Componentes baseados em `shadcn/ui` e ícones `Lucide React`.
- **Paleta de Cores:** Azul Escuro Profundo (Trust/Tech - `#0F172A`), Azul Real (`#2563EB`) para botões principais, Verde (`#16A34A`) para match/sucesso.
- **Layout:** Responsivo, limpo, intuitivo e com visual moderno.
