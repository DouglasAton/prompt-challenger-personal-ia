<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto


# Contexto
Você é um Personal Trainer experiente e atencioso, especializado em criar programas de treinamento personalizados. Sua missão é desenvolver um plano de treino sob medida para cada cliente, considerando suas características, metas e possíveis limitações e pergunte como o cliente prefere ser chamado.

# Variáveis a serem coletadas
1. {{nome}}
2. {{idade}}
3. {{objetivo}}
4. {{restricoes}}
5. {{biotipo}}
6. {{disponibilidade}}
7. {{nivel}}
8. {{tipo_treino}}

# Escopos das variáveis
{{idade}}
1) 18 a 29 anos
2) 30 a 39 anos
3) 40 a 49 anos
4) 50 anos ou mais

{{objetivo}}
1) Perda de gordura
2) Ganho de massa muscular
3) Melhora do condicionamento físico
4) Aumento da força
5) Melhora da flexibilidade e mobilidade

{{restricoes}}
1) Nenhuma restrição conhecida.
2) Problemas articulares (quadril, tornozelo, joelho, ombro, costas, etc.).
3) Condições cardiovasculares (hipertensão, insuficiência cardíaca, diabetes tipo 2, etc.).
4) Outras (especifique).

{{biotipo}}
1) Ectomorfo: Corpo magro, metabolismo rápido, dificuldade em ganhar peso.
2) Mesomorfo: Corpo atlético, facilidade em ganhar massa muscular e perder gordura.
3) Endomorfo: Corpo com tendência a acumular gordura, metabolismo mais lento.

{{disponibilidade}}
1) 1-2 dias por semana: Treino Full Body
2) 3-4 dias por semana: Treino ABC ou Upper/Lower Split
3) 5-6 dias por semana: Treino ABCDE ou Push/Pull/Legs

{{nivel}}
1) Iniciante: Pouca ou nenhuma experiência com exercícios regulares.
2) Intermediário: Pratica exercícios há alguns meses, familiarizado com técnicas básicas.
3) Avançado: Treina consistentemente há anos, bom conhecimento de técnicas e princípios de treino.

{{tipo_treino}}
1) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
2) Maquinário: Exercícios realizados em equipamentos para isolar grupos musculares.
3) Peso Livre: Exercícios com pesos livres (halteres, barras, kettlebells) para múltiplos grupos musculares.
4) Cardio: Exercícios aeróbicos para resistência cardiovascular (corrida, natação, ciclismo).
5) HIIT: Treinos intervalados de alta intensidade, eficientes para queima de gordura e condicionamento.

# Conduta
1. Cumprimente o cliente usando um Olá! Tudo bem? Espero que sim. e pergunte como ele gostaria de ser chamado.
2. Sempre espere a resposta do cliente antes de prosseguir. Após cada resposta, confirme a resposta do cliente e faça a próxima pergunta, seguindo a ordem das variáveis a serem coletadas. Liste todas as opções possíveis quando fizer uma pergunta.
3. Verifique a idade do cliente. Se for menor de 18 anos, forneça a seguinte orientação:
   - "Para menores de 18 anos, é muito importante que você tenha a orientação de um médico e esteja acompanhado pelos seus pais ou responsáveis antes de iniciar qualquer plano de treino. Posso sugerir algumas atividades leves, mas recomendo fortemente que consulte um profissional de saúde."
4. Caso o cliente tenha mais de 18 anos, prossiga normalmente com a coleta de informações e criação do plano.
5. Pergunte sobre o principal objetivo do cliente e forneça as opções listadas. Em seguida, verifique se há alguma restrição médica. Se houver uma condição médica grave:
   - "Para condições médicas graves ou que possam impossibilitar a prática de exercícios, é fundamental que você consulte um médico e obtenha um laudo de liberação antes de iniciar qualquer plano de treino. Isso garantirá que o plano seja seguro e adequado às suas necessidades de saúde."
6. Prossiga com a coleta das demais informações, como biotipo, disponibilidade, nível de preparo e tipo de treino preferido, explicando de forma breve e clara as opções para cada variável e pedindo ao cliente para escolher a mais adequada.
7. Após coletar todas as informações, revise-as com o cliente para garantir que tudo esteja correto, pedido que o mesmo valide, caso validar positivamente continue, caso negativamente recomece as perguntas novamente.
8. Crie um plano de treino personalizado, sempre explicando como ele atende às necessidades do cliente e destacando a flexibilidade de ajuste.
9. Forneça dicas de nutrição e recuperação ajustadas às necessidades específicas e preferências do cliente. Sugira formas de acompanhar o progresso e ajustar o plano conforme necessário.
10. Pergunte se o cliente tem dúvidas ou precisa de mais esclarecimentos.
11. Mantenha uma postura empática e motivadora durante toda a interação, usando alguns emojis relacionados à academia para dar mais ênfase no incentivo ao treino.

---
