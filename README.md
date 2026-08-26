# 📈 Simulador de Investimentos em Fundos Imobiliários (FIIs) em Excel

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Projeto desenvolvido como parte do desafio de código do bootcamp da **[DIO (Digital Innovation One)](https://www.dio.me/)**. O objetivo é criar uma ferramenta prática e interativa em Microsoft Excel para simular o crescimento de patrimônio e o rendimento passivo por meio de dividendos em Fundos de Investimento Imobiliário (FIIs).

---

## 📌 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [Objetivos de Aprendizagem](#-objetivos-de-aprendizagem)
- [Funcionalidades da Planilha](#-funcionalidades-da-planilha)
- [Fórmulas e Conceitos Financeiros Utilizados](#-fórmulas-e-conceitos-financeiros-utilizados)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Como Utilizar](#-como-utilizar)
- [Demonstração / Screenshots](#-demonstração--screenshots)
- [Autora](#-autora)

---

## 🎯 Sobre o Projeto

O mercado de Fundos Imobiliários (FIIs) atrai muitos investidores pelo potencial de geração de renda mensal recorrente via dividendos (proventos). No entanto, calcular o efeito dos juros compostos, reinvestimento de dividendos e aportes mensais ao longo do tempo pode ser complexo.

Esta planilha foi desenvolvida para **automatizar esses cálculos** e responder a perguntas fundamentais do investidor:
- Quanto preciso investir por mês para atingir minha meta financeira?
- Em quanto tempo alcançarei a independência financeira ou uma renda passiva desejada?
- Qual será o impacto do reinvestimento dos dividendos acumulados?

---

## 🎓 Objetivos de Aprendizagem

Durante o desenvolvimento deste laboratório, foram consolidados os seguintes conhecimentos:
- **Modelagem Financeira no Excel:** Aplicação de fórmulas de rendimento e juros compostos.
- **Automação de Cálculos:** Criação de planilhas dinâmicas para simulação de cenários.
- **Documentação Técnica:** Organização e registro de processos técnicos utilizando Markdown no GitHub.

---

## ⚙️ Funcionalidades da Planilha

- **Entrada de Parâmetros Dinâmicos:**
  - Aporte inicial (R$).
  - Aporte mensal (R$).
  - Período do investimento (em anos).
  - Taxa de dividend yield (DY) mensal estimada (%).
- **Cálculos Automáticos:**
  - Valor total investido (soma dos aportes).
  - Patrimônio total acumulado ao longo do tempo.
  - Total de dividendos recebidos no período.
  - Projeção da renda passiva mensal estimada ao final do período.
- **Visão Gráfica:**
  - Gráfico de evolução patrimonial (Patrimônio Acumulado vs. Valor Investido).

---

## 🧮 Fórmulas e Conceitos Financeiros Utilizados

1. **Juros Compostos (Valor Futuro):**
   Utilização do conceito ou da função `=VF()` do Excel para projetar o valor futuro dos aportes acumulados com reinvestimento dos rendimentos.
   
2. **Cálculo de Dividendos Mensais:**
   $$\text{Dividendos Mensais} = \text{Patrimônio Acumulado} \times \text{DY Mensal}$$

3. **Aporte Total:**
   $$\text{Aporte Total} = \text{Aporte Inicial} + (\text{Aporte Mensal} \times \text{Meses})$$

---

## 📁 Estrutura do Repositório

```text
├── images/                  # Capturas de tela e demonstração da planilha
│   ├── dashboard.png
│   └── simulacao_exemplo.png
├── Simulador_Investimento_FIIs.xlsx  # Arquivo Excel da ferramenta
└── README.md                # Documentação técnica do projeto
