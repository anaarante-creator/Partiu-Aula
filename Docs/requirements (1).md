# Requirements --- Partiu Aula

## 1. Identificação do projeto

-   **Nome:** Partiu Aula --- Aplicativo de Caronas para Estudantes
-   **Instituição:** IFTO --- Campus Paraíso
-   **Público-alvo:** estudantes do ensino médio, cursos técnicos,
    institutos federais e universidades.
-   **Integrantes indicados na proposta:** Emilly Roanny, Ana Luísa
    Neiva e Geovanna Gabrielly.
-   **Professor:** Pedro Henrique Amaral.

## 2. Visão geral

O Partiu Aula é uma proposta de aplicativo que conecta estudantes que
precisam de transporte a estudantes que podem oferecer caronas. A
solução pretende facilitar o deslocamento até instituições de ensino,
reduzir os gastos com transporte e incentivar a colaboração entre
alunos.

O problema identificado envolve custos elevados de transporte público ou
privado, longas distâncias, oferta limitada de linhas e horários de
ônibus, atrasos e impacto no orçamento dos estudantes.

## 3. Objetivos do sistema

1.  Permitir que estudantes encontrem caronas compatíveis com sua
    origem, destino, data e horário.
2.  Permitir que estudantes motoristas publiquem ofertas de carona,
    informando trajeto, horário, vagas e valor de contribuição.
3.  Possibilitar a solicitação e o acompanhamento de reservas.
4.  Facilitar a comunicação entre motorista e passageiro.
5.  Permitir a consulta de perfis e avaliações de viagens anteriores.
6.  Reunir as caronas solicitadas e oferecidas em uma área de
    acompanhamento.

## 4. Perfil de usuário e necessidades

### Persona de referência: Ana Clara

-   **Idade apresentada nos documentos:** 17 anos.
-   **Perfil:** estudante do ensino médio integrado em um instituto
    federal, mora longe da instituição e depende de transporte para
    chegar às aulas.
-   **Necessidades:** encontrar caronas confiáveis, economizar dinheiro,
    organizar os horários e chegar às aulas com pontualidade.
-   **Dificuldades:** gastos com transporte, distância entre casa e
    escola, horários rígidos, poucas opções de deslocamento e ônibus
    frequentemente lotados.
-   **Objetivo:** chegar às aulas com praticidade, segurança e menor
    custo financeiro.

## 5. Requisitos funcionais

Os requisitos abaixo consolidam as funcionalidades descritas na
proposta, nos cenários de uso e nas telas do protótipo.

  -----------------------------------------------------------------------
  ID                      Requisito               Descrição
  ----------------------- ----------------------- -----------------------
  RF01                    Cadastro de usuário     O aplicativo deve
                                                  oferecer uma opção para
                                                  o usuário realizar seu
                                                  cadastro.

  RF02                    Login                   O aplicativo deve
                                                  oferecer uma opção para
                                                  o usuário entrar em sua
                                                  conta.

  RF03                    Buscar caronas          O usuário deve poder
                                                  pesquisar caronas
                                                  informando origem,
                                                  destino, data e horário
                                                  desejado.

  RF04                    Exibir resultados       O sistema deve
                                                  apresentar as caronas
                                                  disponíveis que
                                                  correspondam à
                                                  pesquisa.

  RF05                    Consultar detalhes      O usuário deve poder
                                                  visualizar os detalhes
                                                  da carona e as
                                                  informações do
                                                  motorista antes de
                                                  solicitar uma vaga.

  RF06                    Solicitar carona        O passageiro deve poder
                                                  solicitar uma vaga em
                                                  uma carona disponível e
                                                  confirmar o pedido.

  RF07                    Notificar solicitação   O sistema deve enviar
                                                  ao motorista uma
                                                  notificação sobre o
                                                  pedido de carona.

  RF08                    Atualizar situação da   Após a solicitação, o
                          solicitação             sistema deve registrar
                                                  o pedido com status
                                                  pendente, aguardando a
                                                  confirmação do
                                                  motorista.

  RF09                    Oferecer carona         O motorista deve poder
                                                  cadastrar uma oferta
                                                  informando ponto de
                                                  partida, destino,
                                                  horário de saída,
                                                  quantidade de vagas e
                                                  valor de contribuição
                                                  por passageiro.

  RF10                    Validar e publicar      O sistema deve validar
                          oferta                  as informações
                                                  preenchidas e, após a
                                                  publicação,
                                                  disponibilizar a carona
                                                  na busca geral.

  RF11                    Chat interno            O sistema deve permitir
                                                  a troca de mensagens
                                                  entre motorista e
                                                  passageiro em uma
                                                  viagem ativa.

  RF12                    Minhas caronas          O usuário deve poder
                                                  consultar e organizar
                                                  caronas solicitadas,
                                                  oferecidas, próximas e
                                                  passadas/realizadas.

  RF13                    Consultar perfil        O usuário deve poder
                                                  consultar as
                                                  informações do perfil e
                                                  a avaliação média de
                                                  outro usuário.

  RF14                    Avaliar carona          Após o término da
                                                  viagem, o usuário deve
                                                  poder atribuir uma nota
                                                  de 1 a 5 estrelas e
                                                  enviar um comentário.

  RF15                    Atualizar avaliação     O sistema deve
                          média                   registrar a avaliação e
                                                  atualizar a média
                                                  exibida no perfil do
                                                  motorista.

  RF16                    Informar ausência de    Quando nenhuma carona
                          resultados              corresponder à
                                                  pesquisa, o sistema
                                                  deve informar que não
                                                  foram encontradas
                                                  caronas para a rota.

  RF17                    Alertar sobre novas     Na ausência de
                          vagas                   resultados, o sistema
                                                  deve oferecer a
                                                  possibilidade de ativar
                                                  um alerta para novas
                                                  vagas.
  -----------------------------------------------------------------------

## 6. Requisitos não funcionais e critérios de usabilidade

Os documentos não definem métricas técnicas, tecnologias ou níveis
quantitativos de desempenho. Os pontos abaixo registram as
características de qualidade e comportamento de interface que foram
explicitamente propostas:

  -----------------------------------------------------------------------
  ID                      Requisito               Descrição
  ----------------------- ----------------------- -----------------------
  RNF01                   Clareza das mensagens   O sistema deve
                                                  apresentar mensagens
                                                  claras para confirmar
                                                  ações concluídas, como
                                                  o envio de uma
                                                  solicitação.

  RNF02                   Feedback visual         As confirmações devem
                                                  ser acompanhadas de
                                                  destaque visual em
                                                  verde e atualização do
                                                  status da viagem em
                                                  "Minhas Caronas".

  RNF03                   Orientação em caso de   Quando houver erro de
                          erro                    preenchimento, o campo
                                                  incorreto deve ser
                                                  destacado em vermelho e
                                                  acompanhado de uma
                                                  instrução simples.

  RNF04                   Comunicação             O chat deve permitir a
                                                  comunicação entre
                                                  motorista e passageiro
                                                  para combinar detalhes
                                                  do embarque.

  RNF05                   Facilidade de uso       A interface deve
                                                  organizar as funções em
                                                  telas e elementos
                                                  identificáveis,
                                                  conforme o protótipo
                                                  apresentado.

  RNF06                   Apoio à localização do  O sistema deve oferecer
                          encontro                sugestões de pontos de
                                                  referência conhecidos
                                                  próximos às
                                                  escolas/campi para
                                                  reduzir divergências
                                                  sobre o local de
                                                  embarque.
  -----------------------------------------------------------------------

**Observação:** segurança e confiabilidade aparecem como objetivos do
projeto, mas os documentos ainda não especificam mecanismos técnicos
para garanti-las. Autenticação, verificação de identidade, privacidade,
permissões, criptografia, retenção de dados e procedimentos de
emergência precisam ser detalhados em uma etapa posterior.

## 7. Cenários de uso

### 7.1. Busca e reserva de carona

**Situação:** uma estudante precisa garantir transporte para a aula do
dia seguinte e deseja evitar o ônibus lotado.

**Fluxo principal:** 1. A estudante abre o aplicativo e informa origem,
destino e horário desejado. 2. Seleciona "Buscar Caronas". 3. O sistema
exibe a lista de motoristas disponíveis. 4. A estudante seleciona uma
opção e consulta seus detalhes. 5. Seleciona "Solicitar Carona" e
confirma o pedido. 6. O sistema envia uma notificação ao motorista e
registra a solicitação como "Pendente". 7. A solicitação fica disponível
em "Minhas Caronas", aguardando a confirmação do motorista.

**Resultado esperado:** a reserva fica registrada e seu status pode ser
acompanhado pelo usuário.

### 7.2. Cadastro e oferta de carona

**Situação:** um estudante motorista possui vagas livres e deseja
dividir os custos de combustível com outros colegas.

**Fluxo principal:** 1. O motorista acessa "Oferecer Carona". 2. Informa
ponto de partida, destino, horário de saída e quantidade de vagas. 3.
Informa o valor de contribuição sugerido por passageiro. 4. Seleciona
"Publicar Carona". 5. O sistema valida os dados, exibe uma mensagem de
sucesso e adiciona a oferta à busca geral.

**Resultado esperado:** outros estudantes podem encontrar a oferta e
solicitar uma reserva.

### 7.3. Comunicação via chat e avaliação pós-viagem

**Situação:** uma carona foi aceita e passageiro e motorista precisam
combinar o ponto exato de embarque. Depois da viagem, o passageiro
deseja avaliar o motorista.

**Fluxo principal:** 1. O usuário acessa "Minhas Caronas". 2. Abre o
chat da viagem ativa. 3. Envia uma mensagem com o ponto de referência
para o embarque. 4. Após o término da carona, acessa a avaliação. 5.
Seleciona uma nota de 1 a 5 estrelas e envia a avaliação, podendo
incluir comentário. 6. O sistema registra a avaliação e atualiza a média
do perfil do motorista.

**Resultado esperado:** os usuários conseguem combinar detalhes da
viagem e registrar a reputação após o percurso.

## 8. Telas e elementos identificados

A proposta visual apresenta as seguintes telas e áreas:

  -----------------------------------------------------------------------
  Tela/área                           Finalidade e elementos
                                      identificados
  ----------------------------------- -----------------------------------
  Splash / abertura                   Apresentar a identidade visual
                                      "Partiu Aula" e a frase "Juntos no
                                      mesmo destino".

  Login / cadastro                    Permitir entrar ou cadastrar-se; o
                                      protótipo também apresenta opções
                                      de entrada por serviços externos.

  Tela inicial (Home)                 Exibir saudação, atalhos para
                                      buscar carona, oferecer carona e
                                      consultar minhas caronas, além de
                                      próximas caronas.

  Buscar carona                       Reunir campos de origem, destino,
                                      data e horário e o botão de busca.

  Resultados da busca                 Listar caronas disponíveis com
                                      informações do motorista, trajeto,
                                      horário, valor e acesso aos
                                      detalhes.

  Detalhes da carona                  Exibir informações do motorista,
                                      avaliações e rota, com opção para
                                      solicitar reserva.

  Oferecer carona                     Permitir informar partida, destino,
                                      horário, quantidade de vagas e
                                      valor.

  Minhas caronas                      Organizar caronas solicitadas e
                                      oferecidas, com estados como
                                      aguardando e confirmada, e separar
                                      caronas próximas e
                                      passadas/histórico.

  Chat interno                        Exibir a conversa, o histórico de
                                      mensagens e a opção de enviar
                                      mensagem.

  Perfil                              Exibir informações do usuário,
                                      avaliação média, minhas caronas e
                                      avaliações.

  Avaliação                           Permitir atribuir de 1 a 5
                                      estrelas, escrever comentário e
                                      enviar a avaliação.
  -----------------------------------------------------------------------

## 9. Regras e respostas do sistema

-   Uma solicitação de carona deve ficar com status "Pendente" até a
    confirmação do motorista.
-   Uma carona publicada deve aparecer na busca geral.
-   As caronas solicitadas e oferecidas devem poder ser acompanhadas em
    "Minhas Caronas".
-   O chat deve estar acessível a partir da carona ativa.
-   A avaliação deve ser feita após o término da viagem.
-   O sistema deve atualizar a avaliação média do perfil após registrar
    uma nova avaliação.
-   Se houver erro de preenchimento, o sistema deve destacar o campo
    incorreto em vermelho e apresentar uma orientação simples.
-   Se a busca não encontrar opções, o sistema deve exibir a mensagem
    "Nenhuma carona encontrada para esta rota" e oferecer a ativação de
    um alerta para novas vagas.
-   Para confirmar ações, o sistema deve exibir mensagens claras, como
    "Solicitação enviada com sucesso!", com destaque visual e
    atualização do status.

## 10. Diretrizes de interface extraídas do protótipo

O protótipo visual utiliza uma identidade predominantemente verde e
clara, com cartões para apresentar caronas e informações dos usuários.
Entre os elementos visíveis estão:

-   Navegação inferior com áreas como Início, Caronas, botão central de
    ação, Mensagens e Perfil.
-   Botões de ação para buscar, oferecer e consultar caronas.
-   Cartões com nome do motorista, trajeto, horário e valor.
-   Indicadores de situação da carona, como "Aguardando" e "Confirmada".
-   Perfil com iniciais/foto, nome, e-mail e avaliação média.

Essas observações descrevem o protótipo apresentado e não determinam,
por si só, uma implementação técnica específica.

## 11. Validação com usuários

O documento de cenários informa que a equipe apresentou um protótipo de
baixa fidelidade a estudantes com perfil semelhante ao da persona,
solicitando que realizassem as tarefas descritas nos cenários e
registrando dúvidas, erros e facilidades.

A principal dificuldade de usabilidade identificada foi combinar o ponto
exato de encontro. Como resposta proposta, o aplicativo deve oferecer um
chat rápido integrado e sugestões de pontos de referência conhecidos
próximos às escolas/campi.

## 12. Itens que precisam ser definidos

Os documentos de referência não especificam os seguintes pontos. Eles
devem ser discutidos pela equipe antes da implementação:

1.  Quais dados serão obrigatórios no cadastro e como será confirmada a
    condição de estudante.
2.  Como será feita a autenticação e a recuperação de acesso.
3.  Quais informações do perfil serão públicas para outros usuários.
4.  Quais regras definem quem pode oferecer e solicitar caronas.
5.  Como serão tratados cancelamentos, atrasos, ausência do motorista ou
    passageiro e mudanças de rota.
6.  Como será calculado, pago ou apenas combinado o valor de
    contribuição.
7.  Quais notificações serão enviadas e por quais canais.
8.  Como serão tratados bloqueios, denúncias e avaliações inadequadas.
9.  Quais dados de localização serão coletados e por quanto tempo serão
    mantidos.
10. Quais tecnologias, plataformas e requisitos mínimos de dispositivo
    serão adotados.

Esses itens estão registrados como questões em aberto, e não como
funcionalidades já aprovadas.

## 13. Referências utilizadas

Este arquivo foi consolidado a partir dos materiais fornecidos para o
projeto:

-   **Análise de requisitos / protótipo Partiu Aula:** documento visual
    com telas do aplicativo e referência ao protótipo no Figma.
-   **Proposta de Projeto --- Partiu Aula:** descrição e justificativa
    do problema, público-alvo, persona inicial e funcionalidades
    principais.
-   **Cenários de Uso --- Partiu Aula:** cenários de busca e reserva,
    oferta de carona, chat e avaliação, identificação das telas e
    reflexão sobre usabilidade.
