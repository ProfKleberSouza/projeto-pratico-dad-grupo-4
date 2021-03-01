# Especificações Do Projeto

## Personas
|Id        | Persona                                                            |
|----------|--------------------------------------------------------------------|
| ***1***  |Gabriela, 25 anos: é solteira, e trabalha voluntariamente como psicóloga em uma ONG com uma equipe de mais de 20 psicólogos que atendem mais de 40 clientes / pacientes da comunidade. Ela é uma pessoa comunicativa e carismática, tende a ficar entusiasmada com novidades e costuma influenciar outras pessoas rapidamente e contagiá-las com seu ponto de vista. Ela gostaria de ter mais facilidade para realizar a gestão dos atendimentos psicológicos. Seus principais obstáculos estão relacionados ao atendimento, onde todo o gerenciamento das informações da ONG em que trabalha é feito de forma manual ou através de planilhas, o que gera um grande volume de dados descentralizados.
| ***2***  |Vanessa, 40 anos: é casada, trabalha voluntariamente como secretária em uma ONG. É uma pessoa analítica e sistemática, sempre focada em sua organização. Tem um perfil mais tradicional e não está acostumada com tecnologias muito avançadas, mas se esforça para não ficar totalmente desatualizada. Devido ao cenário da pandemia e consequentemente o aumento dos agendamentos das consultas, Vanessa está sempre ocupada com a organização do agendamento das consultas. Ela gostaria de ter total controle dos documentos e da agenda, de maneira que pudesse “bater o olho” e já ter as informações necessárias para exercer seu trabalho. Apesar de ser uma pessoa mais tradicional, Vanessa está tendo dificuldade de conciliar o grande volume de agendamentos feitos hoje, também está encontrando dificuldade de organizar tantos documentos impressos para cada cliente.
| ***3***  |Alexandre, 14 anos: cursando o 9º ano do ensino fundamental e sofre de algumas práticas de violência (verbal e não verbal) por parte de seus “colegas” de classe. Tem dificuldades em se comunicar com os familiares e por conta disso nunca procurou ajuda, o que ocasionou um certo quadro de depressão e ansiedade. É um caso na qual necessita de atenção dos psicólogos.
| ***4***  |Lara, 16 anos: cursando o 3º ano do ensino médio e sofre de ataque de pânico por traumas vivenciados na infância. É uma adolecente com boa convivência na escola, esforçada e se apoia muito em suas amigas. É um caso na qual necessita de atenção dos psicólogos 


## Histórias de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário     |Quero me autenticar no sistema, as funções ficam disponíveis após a autenticação por login e senha                 | Acessar as funcionalidades do sistema |
|Usuário       |Quero poder alterar minha senha do sistema, através de confirmação de e-mail. A senha deve conter uma sequência de caracteres entre letras (maíuscula e minúscula), números e caracteres especiais                | Ter controle das minhas credencias no sistema|
|Psicólogo(a) |Modificar meus dados, com exceção do nome e CRP | Ter controle sobre os meus dados|
|Psicólogo(a) |Visualizar uma lista de horários marcados e em aberto | Manter controle sobre minha agenda|
|Psicólogo(a) |Visualizar os dados do paciente que irei atender e o histórico dos atendimentos dele | Visualizar o laudo dos atendimentos anteriores dos pacientes| 
|Psicólogo(a) |Me cadastrar no sistema, cadastrando o nome, telefone, email, CRP, formação ou previsão de formatura, endereço, horários disponíveis de atendimento, interesse, por onde conheceu o trabalho da ASTLA, sugestão de comentário |Obter acesso ao sistema e participar dos serviços que a ONG oferece |
|Psicólogo(a) |Visualizar o status da minha conta. Caso seja aprovado: tenho acesso as funcionalidades do sistema. Caso seja reprovado: eu consigo visualizar as informações de contato para regularização |Obter um feedback do status do meu cadastro no sistema |
|Secretário(a)|Alterar o status das contas dos membros da comunidade. Os status são definidos como: -aprovado, -reprovado ou -pendente. |Gerenciar as contas dos membros da comunidade cadastrados|
|Secretário(a)|Visualizar relatório de dados da quantidade de horários vagos no mês ou na semana. Também podendo visualizar a quantidade de registros -pendentes, -reprovados e -aprovados de psicólogos(as) e dos membros da comunidade |Obter controle da situação a partir dos dados |
|Secretário(a)|Visualizo uma lista dos membros da comunidade contendo: nome, e-mail, status e CPF, podendo filtrá-los pelo nome, status ou por CPF. Caso necessite alterar o status ou visualizar outros dados, posso acessar uma tela separada com todas as informações | Visualizar as contas dos membros da comunidade cadastrados|
|Secretário(a)|Alterar o status das contas de psicólogos(as). Os status são definidos como: -aprovado, -reprovado ou -pendente. |Gerenciar as contas de psicólogos(as) cadastrados.
|Secretário(a)|Visualizo uma lista dos psicólogos(as) contendo: nome, e-mail, status e CPF, podendo filtrá-los pelo nome, status ou por CPF. Caso necessite alterar o status ou visualizar outros dados, posso acessar uma tela separada com todas as informações | Visualizar as contas dos membros da comunidade cadastrados|
|Secretário(a) |Alocar paciente a um horário de um(a) psicólogos(as), para isso posso visualizar o calendário e a quantidade de profissionais disponíveis para aquele dia         |Permitir criar agendamentos de consultas e assim preencher os horários disponíveis dos psicólogos(as) para atendimento dos pacientes |
|Membro da Comunidade|Me cadastrar no sistema da ONG, informando meus dados. Caso tenha uma limitação de horários| Obter acesso ao sistema e poder receber atendimento psicológico |
|Membro da Comunidade|Posso visualizar o status da minha conta. Caso seja aprovado: tenho acesso as funcionalidades do sistema. Caso seja reprovado: eu consigo visualizar as informações de contato|Obter o feedback do status da minha conta |
|Membro da Comunidade|Visualizar minha lista de horários marcados no sistema|Controlar minha agenda e visualizar minhas consultas marcadas|
|Administrador |Criar, editar e remover contas de psicologos(as). Visualizo uma lista de contas cadastradas contendo nome, e-mail, status e CRP, podendo filtrá-las pelo nome, status ou CRP.         | Permitir o controle sobre as contas dos secretários(as)|
|Administrador|Criar, editar e remover contas de secretários(as). Visualizo uma lista de contas cadastradas contendo nome, e-mail, status e CPF, podendo filtrá-las pelo nome, status ou CPF.         | Permitir o controle sobre as contas dos secretários(as)|

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
