# Especificações Do Projeto



## Personas
|Id        | Persona                                                            |
|----------|--------------------------------------------------------------------|
| ***1***  |Gabriela, 25 anos: é solteira, e trabalha voluntariamente como psicóloga em uma ONG com uma equipe de mais de 20 psicólogos que atendem mais de 40 clientes / pacientes da comunidade. Ela é uma pessoa comunicativa e carismática, tende a ficar entusiasmada com novidades e costuma influenciar outras pessoas rapidamente e contagiá-las com seu ponto de vista. Ela gostaria de ter mais facilidade para realizar a gestão dos atendimentos psicológicos. Seus principais obstáculos estão relacionados ao atendimento, onde todo o gerenciamento das informações da ONG em que trabalha é feito de forma manual ou através de planilhas, o que gera um grande volume de dados descentralizados.
| ***2***  |Vanessa, 40 anos: é casada, trabalha voluntariamente como secretária em uma ONG. É uma pessoa analítica e sistemática, sempre focada em sua organização. Tem um perfil mais tradicional e não está acostumada com tecnologias muito avançadas, mas se esforça para não ficar totalmente desatualizada. Devido ao cenário da pandemia e consequentemente o aumento dos agendamentos das consultas, Vanessa está sempre ocupada com a organização do agendamento das consultas. Ela gostaria de ter total controle dos documentos e da agenda, de maneira que pudesse “bater o olho” e já ter as informações necessárias para exercer seu trabalho. Apesar de ser uma pessoa mais tradicional, Vanessa está tendo dificuldade de conciliar o grande volume de agendamentos feitos hoje, também está encontrando dificuldade de organizar tantos documentos impressos para cada cliente.
| ***3***  |Alexandre, 14 anos: cursando o 9º ano do ensino fundamental e sofre de algumas práticas de violência (verbal e não verbal) por parte de seus “colegas” de classe. Tem dificuldades em se comunicar com os familiares e por conta disso nunca procurou ajuda, o que ocasionou um certo quadro de depressão e ansiedade. É um caso na qual necessita de atenção dos psicólogos.
| ***4***  |Lara, 16 anos: cursando o 3º ano do ensino médio e sofre de ataque de pânico por traumas vivenciados na infância. É uma adolecente com boa convivência na escola, esforçada e se apoia muito em suas amigas. É um caso na qual necessita de atenção dos psicólogos 


> Enumere e detalhe as personas da sua solução. Para
> tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e
> personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário se cadastre no sistema (seja ele membro da comunidade, psicólogo ou membro da secretaria) | ALTA | 
|RF-002| Permitir que o usuário entre no sistema | ALTA | 
|RF-003| Permitir que o usuário atualize os dados que foram preenchidos no cadastro | BAIXA | 
|RF-004| Permitir que o membro da comunidade solicite um atendimento psicológico (preenchendo os dados necessários) | ALTA | 
|RF-005| Permitir que o membro da comunidade desejo participar da chamada pra a consulta agendada | ALTA | 
|RF-006| Permitir que o membro da comunidade desejo receber notificações antes de uma consulta relembrando sobre a data e horário | MÉDIA | 
|RF-007| Permitir que o profissional de psicologia faça o cadastro da sua ficha de informações para atuar no psicólogo  | ALTA |
|RF-008| Permitir que o profissional de psicologia confira os atendimentos agendados | ALTA | 
|RF-009| Permitir que o profissional de psicologia receba lembretes sobre os atendimentos | MÉDIA | 
|RF-010| Permitir que o funcionário da secretaria associe pacientes aos psicólogos disponíveis | ALTA | 
|RF-011| Permitir que o usuário administrador ative e desative os demais usuários do sistema | BAIXA | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móveis | ALTA | 
|RNF-002| O sistema deve notificar os pacientes/psicólogos sobre as consultas em até 15 minutos antes do horário agendado | MÉDIA | 
|RNF-003| O sistema deve possuir uma versão mobile criada com Flutter | ALTA | 
|RNF-004| O sistema deve ser desenvolvido utilizando a biblioteca React para o módulo frontend | MÉDIA | 
|RNF-005| O sistema deve ter uma API REST para processar as requisições do frontend e dos apps mobile | MÉDIA |

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais
>   (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais
>   (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Membros da equipe só devem atuar no projeto aos sábados, domingos, segundas-feiras e terças-feiras |
|03| O projeto é composto de cinco integrantes que dividirão as atividades de desenvolvimento |
|04| Nem todos os membros da equipe de desenvolvimento conhecem todas as tecnologias utilizadas no projeto |
