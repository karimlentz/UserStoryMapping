# Prospecção Tecnológica: User Story Mapping

Este repositório contém a Prova de Conceito (PoC) do trabalho de **Prospecção Tecnológica** da disciplina de Engenharia de Software (GCC188) da Universidade Federal de Lavras (UFLA).

O tema abordado neste trabalho é o **User Story Mapping (USM)**, uma técnica visual essencial para a atuação do *Product Owner* na descoberta de produto, organização de *backlog* e priorização de requisitos.

## Sobre o Projeto:

Diferente de projetos focados puramente em código, o foco desta prospecção é em **Processos e Metodologias Ágeis**. Portanto, a prova de conceito consiste na configuração avançada de uma ferramenta de gestão — o **GitHub Projects** — para emular a estrutura bidimensional de um mapa de histórias de usuário, fugindo do modelo tradicional de *Kanban* (To Do, In Progress, Done).

### O Produto Hipotético:

Para demonstrar a técnica, foi mapeada a jornada de um usuário em um **Site de Envio e Correção de Redações do ENEM**.

## Estrutura Bidimensional do Mapa

Para visualizar o *User Story Map* em ação, acesse a aba [**Projects**](../../projects) deste repositório. O quadro foi estruturado respeitando os princípios da técnica criada por Jeff Patton:

* **Eixo Horizontal (Backbone / Jornada do Usuário):**
  As colunas do quadro não representam o status do trabalho, mas sim as **Atividades** cronológicas que o aluno realiza no sistema:
  1. Cadastro e Assinatura
  2. Submissão da Redação
  3. Acompanhamento da Correção
  4. Recebimento e Análise de Desempenho

* **Eixo Vertical (Slicing / Releases):**
  O fatiamento de valor foi feito utilizando as *Swimlanes* (Raias) do GitHub Projects (agrupadas pelo campo customizado `Release`). As histórias foram distribuídas em:
  * **MVP (Walking Skeleton):** O fluxo essencial para o sistema funcionar de ponta a ponta.
  * **Release 2:** Melhorias de usabilidade e agregação de valor.
  * **Release 3:** Inovação tecnológica e complexidade futura.

* **As Histórias (Issues):**
  Cada cartão no mapa é uma *Issue* representando uma História de Usuário. Ao clicar em uma *Issue*, é possível verificar os **Critérios de Aceitação** e a quebra de **Tarefas Técnicas** (Front-end, Back-end e Banco de Dados), garantindo a rastreabilidade entre negócio e engenharia.

## Para navegar na estrutura bidimensional, siga estes passos:

1. Clique na aba **Projects** no menu superior deste repositório.
2. Abra o projeto **"User Story Mapping - Site de Redações"** (ou o nome que você definiu para o projeto).
3. Observe a visualização em *Board*, notando o cruzamento entre as etapas da jornada (colunas) e as entregas (linhas horizontais/raias).
4. Clique em qualquer cartão (ex: `Como usuário, quero enviar minha redação...`) para visualizar o detalhamento dos requisitos daquela história específica.
