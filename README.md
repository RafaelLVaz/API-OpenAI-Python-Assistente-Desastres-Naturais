#  ChatGPT Especializado para Vítimas de Desastres Naturais

Este projeto tem como objetivo desenvolver um chatbot com base na API do ChatGPT, voltado para auxiliar vítimas de desastres naturais como enchentes, deslizamentos e terremotos. O modelo responde de forma contextualizada, dividindo suas orientações em três fases: **antes**, **durante** e **depois** do desastre.

---

##  Objetivos do Projeto

- Aplicar fundamentos de LLMs (Modelos de Linguagem de Grande Escala)
- Utilizar a API da OpenAI (ChatGPT) para gerar respostas empáticas e seguras
- Criar prompts contextualizados conforme a fase do desastre
- Utilizar fontes oficiais para embasar as respostas do assistente

---

##  Tecnologias Utilizadas

- Python
- Few-Shot-Leaning
- OpenAI API (modelo GPT-4o mini)
- Google Colab

---

##  Fontes Utilizadas

As respostas do chatbot foram construídas com base em fontes confiáveis de segurança e saúde pública:

- [Cruz Vermelha – Guia sobre sismos](https://www.cruzvermelha.pt/images/pdf/folhetosismos2016.pdf)
- [UFSC – Manual de boas práticas em inundações e deslizamentos](https://www.ceped.ufsc.br/wp-content/uploads/2014/10/boas_praticas_0.pdf)
- [Medicar – Dicas de saúde durante chuvas e enchentes](https://medicar.com.br/como-agir-em-situacoes-de-chuvas-enchentes-e-tempestades/)
- [Defesa Civil RS – Ações preventivas e dicas](https://defesacivil.rs.gov.br/acoes-preventivas-e-dicas)
- [CETESB – Prevenção de desastres naturais](https://cetesb.sp.gov.br/proclima/wp-content/uploads/sites/36/2014/05/prevencaodedesastresnaturaisconceitosbasicos.pdf)

---

##  Estrutura dos Prompts

### 🔹 Antes do Desastre (Prevenção)
- “O que devo fazer se houver risco de enchente na minha região?”
- “Como montar um kit de emergência?”
- “É seguro continuar morando perto de uma encosta com rachaduras?”

### 🔹 Durante o Desastre (Resposta Imediata)
- “A água começou a entrar em casa, o que eu faço?”
- “Estou ouvindo um estrondo vindo do morro, devo evacuar?”
- “Estou em um local alto, mas sem comida nem água. O que devo priorizar?”

### 🔹 Depois do Desastre (Recuperação)
- “Posso voltar para casa depois da enchente?”
- “Como evitar doenças após o contato com água contaminada?”
- “Perdi meus documentos, onde posso buscar ajuda?”

---

##  Exemplos de Análise de Prompt

###  Prompt: *O que fazer se minha casa alagar?*

**Resposta Gerada**:
- Mantenha a calma  
- Desligue a energia (se possível)  
- Mova itens importantes  
- Prepare um kit de emergência  
- Siga orientações da Defesa Civil  
- Evacue se necessário  
- Evite áreas inundadas  
- Comunique-se com familiares ou serviços de emergência

**Pontos Positivos**:
- Tom calmo e orientador
- Instruções práticas e claras
- Encorajamento ao uso de fontes oficiais

**Melhorias Sugeridas**:
- Incluir fontes específicas (ex: app da Defesa Civil)
- Citar rádios ou canais oficiais de alerta

---

###  Prompt: *O que fazer se eu passar por um terremoto numa viagem ao Japão?*

**Resposta Gerada**:
- Proteja-se sob móveis firmes  
- Afaste-se de janelas  
- Vá para áreas abertas (se estiver na rua)  
- Pare o carro em segurança (se estiver dirigindo)  
- Verifique ferimentos após o tremor  
- Cuidado com réplicas  
- Instale apps de alerta  
- Estude rotas de emergência antes da viagem

**Pontos Positivos**:
- Organização clara (antes, durante, depois)  
- Cobre diferentes cenários  
- Estimula preparo antecipado

**Melhorias Sugeridas**:
- Citar apps específicos (Yurekuru Call, NHK Alerts)  
- Considerar barreiras linguísticas e dar dicas práticas

---

##  Conclusão

Este projeto demonstra o uso de IA generativa aplicada em situações críticas, com foco na responsabilidade social e na utilidade prática. O chatbot se mostrou capaz de gerar respostas empáticas, seguras e fundamentadas, respeitando as etapas de cada desastre natural.

---

## 📌 Como Executar

1. Clone este repositório  
2. Instale a biblioteca da OpenAI:
   ```bash
   pip install openai
