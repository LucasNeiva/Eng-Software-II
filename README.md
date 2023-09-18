# Briefing GetSamurai
## Participantes

- Afonso Henrique

- Arthur Motter

- Edson Mitsuru

- Gustavo Mota

- Lucas Neiva
  
## Resumo:

O sistema consiste de um marketplace online que tem como objetivo conectar profissionais autônomos (freelancers) a empresas e profissionais que buscam serviços sob demanda.

 A plataforma permite que freelancers de diferentes áreas, como design, programação e marketing, criem perfis destacando suas especialidades, portfólio de trabalho e valores cobrados.

 Do outro lado, empresas e profissionais que precisam contratar serviços pontuais podem pesquisar e encontrar freelancers ideais para seus projetos, enviando propostas de trabalho e negociando os detalhes da contratação.
 Dentro do sistema, freelancers podem gerenciar seus projetos em andamento, receber pagamentos e avaliar os contratantes depois da finalização dos trabalhos. Já os contratantes podem acompanhar o progresso, aprovar entregas e avaliar o trabalho dos freelancers.

 O objetivo é facilitar a conexão entre profissionais autônomos e aqueles que buscam serviços sob demanda, provendo um sistema transparente, confiável e com recursos para gerenciamento de projetos e pagamentos, trazendo benefícios para ambos os lados.

## Requisitos do sistema (MVP)

- Cadastro completo de perfis
  - Freelancer informa especialidades, formação, portfólio, valor da hora trabalhada
  - Contratante informa ramo, localização, equipe, objetivos a serem cumpridos
- Busca e filtros
  - Contratantes buscam freelancers por habilidade, localização, valores cobrados
  - Opções de ordenação por avaliação, preço, experiência
- Envio e aceitação de propostas
  - Contratante envia proposta detalhando projeto, prazo e orçamento
  - Freelancer pode aceitar ou recusar proposta, além de negociar detalhes
- Gerenciamento de projetos
  - Acompanhamento de entregas e prazos
  - Freelancer envia atualizações e pede aprovação em marcos
- Pagamentos
  - Integração com gateways de pagamento
  - Contratante pode pagar pelo serviço por completo após o contrato ser fechado ou durante o período do serviço, no caso de serviços de longa duração
  - Freelancer recebe o pagamento após conclusão do serviço ou de maneira periódica, no caso de serviços de longa duraçao
- Avaliações
  - Após finalização, ambos avaliam experiência de trabalho
  - Avaliações publicadas no perfil para consulta
- Notificações
  - Alertas por e-mail sobre propostas recebidas, pagamentos efetuados etc
- Painel de controle
  - Dashboard com projetos, finanças, avaliações de cada usuario

## Perfis

- Freelancer: cadastra perfil, recebe propostas de projeto, avalia contratantes após finalização.
- Contratante: cadastra empresa, busca e seleciona freelancers, envia propostas, avalia freelancers após finalização.

## Tecnologias

- Front-end em React
- Banco de dados Oracle
- Hospedagem em servidores na nuvem
- Node.js
- Javascript

## Responsividade

- Layout responsivo para telas a partir de 360px de largura
- ignorar resoluções menores que 360px

## Observações

- Em versões posteriores: recursos adicionais de gerenciamento de projetos.
- Monetização via comissão sobre transações realizadas e sob publicidade e anúncios de serviços.

## Diagrama de casos de uso
![image](https://github.com/lucasneiva/Eng-Software-II/assets/105697480/5c891633-a208-47ea-a998-b80207334533)
