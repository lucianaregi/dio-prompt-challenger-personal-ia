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
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer Automatizado</h3>
Este projeto é um **assistente de personal trainer automatizado** que gera planos de treino personalizados para usuários. Com base nas informações fornecidas, como nome, idade, peso, altura, biotipo corporal, disponibilidade de tempo, entre outras, o assistente cria um plano de treino ajustado para atender aos objetivos de cada usuário, como ganho de massa muscular, perda de peso, ou definição muscular.

O assistente utiliza variáveis para armazenar as respostas e recomendações, permitindo uma integração fácil em sistemas automatizados. 
</p>
---

## 🌐 Tecnologias utilizadas

Amazon Bedrock: Plataforma dedicada à criação e implementação de assistentes virtuais de personal trainer.

Engenharia de Prompts: Desenvolvimento de prompts organizados para facilitar a interação com o modelo.


---
## 📝 Estrutura de Variáveis

O assistente utiliza as seguintes variáveis para personalizar o plano de treino:
| Variável | Descrição |
| --- | --- |
| `{{nome}}` | Nome do usuário |
| `{{idade}}` | Idade do usuário |
| `{{peso}}` | Peso do usuário (em kg) |
| `{{altura}}` | Altura do usuário (em metros) |
| `{{classificação_IMC}}` | Classificação do IMC calculado |
| `{{recomendacao_IMC}}` | Recomendação de treino com base no IMC |
| `{{biotipo}}` | Biotipo corporal (Ectomorfo, Mesomorfo, Endomorfo) |
| `{{dias_treino}}` | Número de dias que o usuário pode treinar por semana |
| `{{tempo_sessao}}` | Tempo disponível para cada sessão de treino |
| `{{tempo_total_treino}}` | Tempo total de treino semanal calculado |
| `{{tipo_exercicio}}` | Tipo de exercício preferido pelo usuário |
| `{{objetivo}}` | Objetivo do usuário (Ganho de Massa, Perda de Peso, etc.) |
| `{{nivel_experiencia}}` | Nível de experiência (Iniciante, Intermediário, Avançado) |
| `{{lesoes_restricoes}}` | Histórico de lesões ou restrições físicas |
| `{{preferencia_exercicio}}` | Preferência entre resistência muscular ou explosão |
| `{{descricao_plano}}` | Descrição personalizada do plano de treino |
| `{{sugestao_progressao}}` | Sugestão de progressão nos treinos |
| `{{saudacao_inicial}}` | Saudação inicial personalizada com base na hora do dia |

---

## 📖 Exemplo de Interação

Assistente: Bom dia! Vamos criar um plano de treino personalizado para você. Antes de começarmos, preciso de algumas informações para garantir que o plano se encaixe perfeitamente nas suas necessidades.

Assistente: Qual é o seu nome?
Usuário: Ana

Assistente: Quantos anos você tem?
Usuário: 32

Assistente: Qual é o seu peso em kg?
Usuário: 68

Assistente: Qual é a sua altura em metros?
Usuário: 1.65

Assistente: Com base nas suas informações, seu IMC é de 24.98. Isso classifica você como Peso Normal. Como seu IMC está na faixa de Peso Normal, é recomendado que você comece com um plano de treinos equilibrado, variando entre treinos de resistência e ganho de massa muscular.

...

Resumo do Plano de Treino:
| Dia        | Tipo de Treino | Grupo Muscular     | Séries | Repetições | Duração |
|------------|----------------|--------------------|--------|------------|---------|
| Segunda    | Full Body      | Corpo Inteiro      | 3      | 15         | 1 hora  |
| Quarta     | ABC - A        | Peito e Costas     | 4      | 12         | 1 hora  |
| Sexta      | ABC - B        | Pernas e Ombros    | 4      | 12         | 1 hora  |

---
Detalhamento dos Exercícios:

#### Exercício 1 - Supino Reto com Halteres:
Descrição: Deite-se em um banco plano, segure os halteres com as palmas voltadas para a frente e empurre para cima até que os braços estejam estendidos.
Sugestão de Carga: Moderada
Séries: 4 | Repetições: 12
Justificativa: Este exercício é ideal para fortalecer o peitoral, ajudando na definição muscular, que é o objetivo de Ana. Como ela tem 32 anos e um nível intermediário, pode ser realizada com cargas moderadas.
#### Passo a Passo:
Deite-se em um banco com os pés firmemente no chão.
Segure os halteres na altura dos ombros, com as palmas voltadas para a frente.
Empurre os halteres para cima, estendendo os braços.
Abaixe os halteres lentamente até a posição inicial.
Aquecimento: 5 minutos de caminhada leve para ativar o corpo.
Alongamento Pós-Treino: Realize 2 séries de 30 segundos de alongamento para peitoral e ombros.

Assistente: Gostaria de ajustar algum aspecto do plano, como a intensidade dos exercícios ou adicionar mais sessões de cardio?
Usuário: Sim, gostaria de dicas para progredir nos treinos.
Assistente: Ótimo, Ana! Aqui está uma sugestão de progressão: 'Aumente a carga em 5% a cada duas semanas para continuar desafiando seus músculos e melhorando a definição.'


---
## Licença
Este projeto está licenciado sob a Licença MIT.

---
## Autor
Desenvolvido por <a href="https://github.com/lucianaregi">Luciana Rocha</a>
