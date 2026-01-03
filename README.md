# 🚀 Smart Lead Scoring: Inteligência Artificial para Real Estate

[![Testar Simulador](https://img.shields.io/badge/🤖_Simulador-Testar_Agora-brightgreen?style=for-the-badge)](https://CaioHenrique28.github.io/triagem_leads/)

Este projeto apresenta uma solução avançada de **Automação de Vendas e Inteligência de Dados** desenvolvida para o setor imobiliário de alto padrão. O sistema utiliza IA Generativa para identificar intenções de compra ocultas e priorizar leads com alto potencial de conversão.

---

## 📺 Demonstração do Sistema
Veja o fluxo completo: desde o preenchimento do formulário pela cliente (Dra. Helena, com potencial de R$ 5.5M) até à recepção do relatório detalhado no Gmail.

https://github.com/CaioHenrique28/triagem_leads/raw/main/assets/triagem_leads.mp4

*(Nota: O vídeo acima será reproduzido automaticamente após o upload para a pasta assets e a configuração correta do link)*

---

## 💡 O Problema de Negócio
Muitos leads de alto padrão são perdidos porque os filtros convencionais de formulários (Google Forms, Typeform) são rígidos. Um investidor pode selecionar "Aluguel" apenas para avançar rápido, fazendo com que o corretor ignore uma oportunidade milionária.

## 🧠 A Solução Técnica
Criei uma arquitetura que utiliza o **Google Gemini 2.5 Flash** para realizar uma triagem qualitativa baseada em **Processamento de Linguagem Natural (NLP)**.

### Diferenciais Técnicos:
* **Regra de Ouro (Data Priority):** O motor de IA prioriza o campo de comentário livre sobre as opções fechadas do formulário.
* **Sanitização com JavaScript:** Nó de código personalizado para tratar dados nulos e realizar o merge de informações entre o Webhook e a IA.
* **Segurança (PII & Injection):** Implementação de salvaguardas no prompt para evitar manipulação do modelo e proteção de dados sensíveis.

---

## 🛠️ Stack Tecnológica
* **Orquestração:** n8n
* **Inteligência Artificial:** Google Gemini 2.5 Flash
* **Base de Dados:** MongoDB Atlas (NoSQL)
* **Linguagem:** JavaScript (Node.js)

---

## 👨‍💻 Sobre o Autor
**Caio** - Engenheiro de Dados com 12 anos de experiência técnica.
* Especialista em infraestrutura de dados e automação de processos.
* Focado na integração de LLMs para geração de valor real em negócios.
* Atualmente desenvolvendo soluções de IA aplicadas ao mercado imobiliário e financeiro.

---

## 📂 Como Replicar este Projeto
1.  Importe o ficheiro `workflow.json` no seu n8n.
2.  Configure as credenciais para o Google AI Studio, MongoDB e Gmail.
3.  Utilize o Webhook gerado como destino do seu formulário.
