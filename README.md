# 🚀 Smart Lead Scoring: Inteligência Artificial para Real Estate

[![Testar Simulador](https://img.shields.io/badge/🤖_Simulador-Testar_Agora-brightgreen?style=for-the-badge)](https://CaioHenrique28.github.io/triagem_leads/)

Este projeto apresenta uma solução de **Inteligência de Dados e Automação** de alto impacto para o mercado imobiliário. O sistema utiliza IA Generativa para identificar intenções de compra de luxo que são frequentemente ignoradas por filtros rígidos de formulários convencionais.

---

## 📺 Demonstração do Fluxo (Vídeo)
Abaixo, veja o sistema a processar em tempo real um lead VIP (Dra. Helena). Note como a IA ignora o campo "Aluguer" do formulário para focar na intenção de compra de **R$ 5.5 milhões** descrita no comentário.

<video src="https://github.com/CaioHenrique28/triagem_leads/raw/main/assets/triagem_leads.mp4" width="100%" controls>
  O seu navegador não suporta a reprodução de vídeos. 
  <a href="https://github.com/CaioHenrique28/triagem_leads/raw/main/assets/triagem_leads.mp4">Clique aqui para descarregar o vídeo</a>.
</video>

---

## 💡 O Problema de Negócio
No setor imobiliário de alto padrão, a velocidade e a precisão na triagem são críticas. Muitos investidores preenchem formulários de forma apressada. Um lead com potencial de milhões pode ser classificado como "frio" apenas por selecionar uma opção padrão, resultando em perda de receita.

## 🧠 Solução Técnica e Diferenciais
Desenvolvi uma arquitetura de dados utilizando o **Google Gemini 2.5 Flash** integrada via **n8n**:

* **Regra de Ouro (Prioridade de Intenção):** O motor de IA foi instruído a dar prioridade absoluta ao processamento de linguagem natural (comentários) sobre os dados estruturados do formulário.
* **Merge de Dados com JavaScript:** Implementação de um nó de código em Node.js para garantir a integridade dos dados e realizar a fusão entre a análise da IA e os dados de contacto do Webhook.
* **Segurança e Resiliência:** O fluxo conta com salvaguardas contra *Prompt Injection* e sanitização de dados para evitar falhas em caso de valores nulos.

---

## 🛠️ Stack Tecnológica
* **Orquestração:** n8n
* **IA Generativa:** Google Gemini 2.5 Flash (via API)
* **Base de Dados:** MongoDB Atlas (NoSQL)
* **Linguagem:** JavaScript / Node.js

---

## 👨‍💻 Sobre o Autor
**Caio** - Engenheiro de Dados com 12 anos de experiência.
* Especialista em infraestrutura de dados e automação inteligente.
* Focado em transformar modelos de linguagem (LLMs) em ferramentas práticas de negócio.
* Desenvolvendo soluções de vanguarda para o mercado imobiliário e de investimentos.

---

## 📂 Estrutura do Repositório
* `/assets`: Media e demonstrações.
* `/docs`: Código-fonte do simulador interativo (GitHub Pages).
* `workflow.json`: Ficheiro de importação para o n8n.
