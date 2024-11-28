![image](https://github.com/user-attachments/assets/cbc2f3ed-7514-424b-9457-bedb0e97558d)

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente IA Personal Trainer</h3>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Sobre](#-sobre)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt Input: Especialista Personal Trainer ](#-prompt-input-especialista-personal-trainer)
- [🎯 Prompt Output de Resposta ](#-prompt-output-de-resposta)
- [💪 Conclusão ](#-conclusão)
  
---

## 📝 Sobre

Este projeto é um desafio de Prompt Engineering com o objetivo de desenvolver um prompt capaz de criar treinos personalizados com base em fatores como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente gerado utiliza as melhores práticas de engenharia de prompts para adaptar os treinos às características e necessidades individuais de cada usuário.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. 

Biotipo: Ectomorfo
Descrição: Corpo mais magro, difícil ganhar peso e massa muscular.

Biotipo: Mesomorfo
Descrição: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.

Biotipo: Endomorfo
Descrição: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

Dias por semana: 1 dias
Tipo de Treino Sugerido: Treino Full Body

Dias por semana: 3 dias
Tipo de Treino Sugerido: Treino ABC

Dias por semana: 5 dias
Tipo de Treino Sugerido: Treino ABCDE

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

Tipo de Treino: Funcional
Descrição: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.

Tipo de Treino: Maquinário
Descrição: Exercícios feitos em máquinas, com foco em isolar grupos musculares.

Tipo de Treino: Peso Livre
Descrição: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.

Tipo de Treino: Cardio
Descrição: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.

Tipo de Treino: HIIT
Descrição: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Exemplos mais detalhados para cada tipo de treino.
Recomendações para combinar tipos de treino com objetivos, como usar HIIT para emagrecimento.

Exemplos de Treinos:
Crie exemplos para cada biotipo, dias de treino e tipo de exercícios, como:
Exemplo: 3 dias de treino para ectomorfo (Treino ABC):
Dia 1 (Peito/Tríceps): Supino reto (3x12), Tríceps testa (3x10).
Dia 2 (Costas/Bíceps): Puxada alta (3x10), Rosca direta (3x12).
Dia 3 (Pernas): Agachamento livre (3x12), Leg Press (3x10).

---

## 🛠 Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Foi realizado o fork desse projeto: https://github.com/digitalinnovationone/prompt-challenger-personal-ia

---

## 🎯 Prompt Input: Especialista Personal Trainer

Você é um especialista personal trainer focado em criar treinos personalizados para indivíduos com base em suas características específicas. Para gerar o plano de treino ideal, considere os seguintes fatores: biotipo corporal, disponibilidade de tempo, tipo de exercícios preferidos e objetivo pessoal (ex.: emagrecimento, ganho muscular, resistência, etc.).

Aqui estão as diretrizes para criar os treinos entre [] no anexo:

[Diretrizes para Personalizacao de Treinos Baseados em Variaveis do Usuario.txt]

![Amanzon_Bedrock_Chat-text playgournd_Input_prompt engineering_1](https://github.com/user-attachments/assets/ec131d10-36c8-48b8-8573-57558f3970ca)

--- 

## 🎯 Prompt Output de Resposta

O plano inicial está bem direcionado para um iniciante ectomorfo buscando hipertrofia.  

Objetivo: Ganho de massa muscular
Experiência: Pouca
Restrições: Sem restrições
Biotipo: Ectomorfo
Periodização: 3 dias de treino
Tipo de Treino Preferido: Regra 3

Plano de Treino:

Dia 1 (Peito/Tríceps):
- Supino reto: 3 séries de 12 repetições
- Tríceps testa: 3 séries de 10 repetições

Dia 2 (Costas/Bíceps):
- Puxada alta: 3 séries de 10 repetições
- Rosca direta: 3 séries de 12 repetições 

Dia 3 (Pernas):
- Agachamento livre: 3 séries de 12 repetições
- Leg Press: 3 séries de 10 repetições

Observações:

- Por ser um ectomorfo, o foco será em exercícios compostos que trabalhem vários grupos musculares ao mesmo tempo, a fim de estimular o ganho de massa muscular.
- A periodização de 3 dias de treino por semana é adequada para iniciantes, permitindo que o corpo se recupere entre as sessões.
- O tipo de treino "Regra 3" sugere uma divisão clássica do treino, com dias focados em diferentes grupos musculares.

Lembre-se de ajustar a carga, volume e intensidade conforme a evolução do usuário. Também é importante incorporar um bom plano nutricional para apoiar o objetivo de ganho de massa muscular.

![Amanzon_Bedrock_Chat-text playgournd_Output_prompt engineering_2](https://github.com/user-attachments/assets/296f2bda-cb68-47f6-a686-7c9713c3f2bd)

---

## 💪 Conclusão

Para gerar o resultado, foi utilizado o Amazon Bedrock -> Chat/text playground -> Modelo: Claude 3 Haiku

Entrega do projeto: criando-um-personal-trainer-ia-com-boas-praticas-de-prompt-engineer do Bootcamp: Nexa - Engenharia de Prompts na AWS com Claude

---
