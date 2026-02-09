# Resultados-Prompts

# 📌 Projeto: Entrevista de Carreira em Tecnologia

## 🎯 Objetivo do Projeto
O objetivo foi **descobrir o perfil profissional de uma pessoa interessada em tecnologia** por meio de uma entrevista estruturada de 7 perguntas.  
A partir das respostas, a IA analisou interesses, experiência, disponibilidade e objetivos para sugerir **3 carreiras promissoras**, ranqueadas com base em afinidade, demanda de mercado e aproveitamento da experiência prévia.

---

## 🤖 Como a IA foi utilizada
- **Prompts:**  
  Foram criadas perguntas guiadas, uma por vez, seguindo um roteiro pré-definido (7 etapas).  
  Exemplo: *"No seu dia a dia, você prefere lidar mais com pessoas, dados ou código?"*

- **Lógica:**  
  - Coleta das respostas em sequência.  
  - Aplicação de uma matriz de decisão (0–5 pontos por critério).  
  - Ranqueamento das carreiras com pontuação final (0–20).  
  - Apresentação estruturada com vantagens, desafios e contexto de mercado.  

- **Ferramentas:**  
  - Estrutura de entrevista (perguntas e respostas).  
  - Análise de perfil com base em critérios objetivos.  
  - Pesquisa de mercado para complementar com oportunidades reais de estágio e júnior.  

---

## 💬 Exemplos de Perguntas e Respostas

**Pergunta 1:**  
*"O que mais te atrai em tecnologia — resolver problemas, criar produtos ou entender sistemas?"*  
**Resposta:** resolver problemas  

**Pergunta 4:**  
*"No seu dia a dia, você prefere lidar mais com pessoas, dados ou código?"*  
**Resposta:** dados  

**Pergunta 6:**  
*"Quais assuntos ou tecnologias mais despertam seu interesse?"*  
**Resposta:** dados, inteligência artificial e aplicativos de celular  

**Pergunta 7:**  
*"Você tem alguma experiência prévia (mesmo que não seja em tecnologia) que gostaria de aproveitar nessa nova jornada?"*  
**Resposta:** Eu trabalho com Publicidade  

---

## 🔄 Como reproduzir ou entender a solução

1. **Definir o roteiro de entrevista**  
   - 7 perguntas fixas, uma por vez.  
   - Garantir que o usuário responda antes de avançar.  

2. **Coletar respostas**  
   - Registrar interesses, experiência, disponibilidade e objetivos.  

3. **Aplicar matriz de decisão**  
   - Avaliar cada carreira em 4 critérios:  
     - Afinidade com interesses  
     - Demanda de mercado  
     - Tempo até júnior (ramp-up)  
     - Aproveitamento da experiência prévia  
   - Somar pontos (0–20).  

4. **Gerar ranking de carreiras**  
   - Apresentar 3 opções com explicação personalizada.  
   - Estruturar vantagens, desafios e contexto de mercado.  

5. **Pesquisa de mercado complementar**  
   - Buscar vagas júnior e estágio em plataformas como **VagasPraJr, Indeed, Vagas.com**.  
   - Relacionar oportunidades com o perfil do candidato.  

6. **Handoff para especialista (Agent 2)**  
   - Após escolha da carreira, transferir informações para criação de plano de estudos personalizado.  

<img width="1057" height="564" alt="image" src="https://github.com/user-attachments/assets/ae52b041-7ae6-493a-b902-83c0616ff84d" />

---

# AGENT 2 - Planejador de Carreiras

# 📊 Projeto: Trilha de Estudos em Ciência de Dados (120 dias)

## 🎯 Objetivo do Projeto
Este projeto tem como objetivo documentar e compartilhar uma **trilha de estudos de 120 dias** para transição de carreira em **Ciência de Dados**, integrando:
- GitHub como primeira etapa (versionamento e portfólio).
- Fundamentos de programação e estatística.
- Cursos práticos de **JavaScript, C# e SQL Server**.
- Projetos aplicados em Python e Machine Learning.
- Preparação para entrevistas técnicas e publicação de portfólio.

---

## 🤖 Como a IA foi Utilizada
A inteligência artificial foi usada para:
- **Prompts**: receber informações sobre carreira, horas semanais, experiência e objetivos.
- **Lógica**: estruturar o roadmap em blocos (fundamentos, prática, portfólio, entrevistas).
- **Ferramentas**: gerar planilha Excel com cronograma detalhado, tópicos de estudo e recursos complementares.
- **Personalização**: incluir cursos gratuitos do YouTube e checklist de GitHub para consolidar o portfólio.

---

## 💬 Exemplos de Perguntas e Respostas

**Pergunta:**  
“Poderia colocar o GitHub em primeiro para que eu comece a ter meus estudos no GitHub?”  

**Resposta:**  
O roadmap foi reorganizado para colocar GitHub como foco das semanas 1–2, com tarefas práticas (criar conta, configurar SSH, commits, README).  

---

**Pergunta:**  
“Monte uma lista para curso de JavaScript para Iniciantes, C# Curso Completo para iniciante, SQL Server para iniciantes.”  

**Resposta:**  
Foi criada uma lista estruturada com módulos, tópicos, exercícios práticos e projetos sugeridos para cada linguagem.  

---

**Pergunta:**  
“Poderia pensar melhor na trilha e detalhar os tópicos em uma planilha de Excel?”  

**Resposta:**  
A IA produziu uma planilha Excel com 7 abas (Resumo, Cronograma, JS, C#, SQL, GitHub & Portfólio, Recursos), detalhando cada semana e cada módulo.  

---

**Pergunta:**  
“Poderia relacionar 3 cursos do YouTube na planilha?”  

**Resposta:**  
Foram adicionados três cursos gratuitos:  
- JavaScript – Curso em Vídeo (Gustavo Guanabara)  
- C# – balta (canal balta)  
- SQL Server – Webmundi  

---

## 🔄 Como Reproduzir ou Entender a Solução

1. **Definir parâmetros iniciais**: carreira escolhida, horas semanais, experiência, objetivo, preferências e interesses.  
2. **Usar IA para estruturar roadmap**: dividir em blocos (fundamentos, prática, portfólio, entrevistas).  
3. **Gerar planilha Excel** com cronograma detalhado e tópicos de estudo.  
4. **Seguir cronograma**: dedicar 18h/semana, com commits frequentes no GitHub.  
5. **Publicar portfólio**: ao final, usar GitHub Pages e LinkedIn para mostrar projetos.  

---

✨ Este README documenta a jornada de aprendizado e serve como guia para quem deseja **reproduzir ou adaptar a trilha de estudos** em Ciência de Dados.


✅ Dessa forma, qualquer pessoa pode reproduzir a solução:  
- Seguindo o roteiro de entrevista,  
- Aplicando a matriz de decisão,  
- E conectando com dados reais de mercado para validar oportunidades.

  <img width="1049" height="577" alt="image" src="https://github.com/user-attachments/assets/5738ed02-f3f1-4cd3-aa29-d0422c7a02da" />

