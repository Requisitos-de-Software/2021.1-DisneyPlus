# Forward-from

## 1. Introdução
Forward-From é a etapa onde ligamos os Requisitos e artefatos de desenho e implementação. O grupo optou por utilizar meta-modelo de Toranzo.

## 2. Legenda

### 2.1. Classificação da Categoria
Ambiental: congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido;

Organizacional: reune informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema;

Gerencial: agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto;

Desenvolvimento, Gerencial: abarca informações relacionadas aos diversos artefatos gerados no processo de Desenvolvimento, Gerencial;

## 3. Requisitos Funcionais


| Número | Requisito                                                  | História de Usuário   | Léxico | Cenário | Categoria |
|--------|------------------------------------------------------------|-----------------------|----------------------------------------|---------   |-----------|
|  RF1   | O usuário deve poder criar um perfil                       |         US10          |L06 - Criar, L30 - Perfil, L50 - Usuário| C01 - Criar Perfil|Gerencial, Desenvolvimento|
|  RF2   | O usuário deve poder realizar login                        |         US02          |L25 - Login, L50 - Usuário|C02 - Realizar Login       |Gerencial, Desenvolvimento|
|  RF3   | O usuário deve poder criar uma conta                       |         US01          |L06 - Criar, L04 - Conta, L50 - Usuário|C03 - Criar Conta |Gerencial, Desenvolvimento|
|  RF4   | O usuário deve poder assistir títulos                      |         US19          |L03 - Assistir, L49 - Título, L50 - Usuário|C04 - Assistir títulos|Gerencial, Desenvolvimento|
|  RF5   | O usuário deve poder realizar logout                       |         US03          |L26 - Logout, L50 - Usuário|C05 - Realizar logout|Gerencial, Desenvolvimento|
|  RF6   | O usuário deve poder pesquisar títulos                     |         US20          |L32 - Pesquisar, L49 - Título, L50 - Usuário|C06 - Pesquisar Títulos|Gerencial, Desenvolvimento|
|  RF7   | O usuário deve poder recuperar sua senha                   |         US04          |L42 - Senha, L50 - Usuário|C07 - Recuperar senha||Gerencial, Desenvolvimento|
|  RF8   | O usuário deve poder selecionar um perfil                  |         US11          |L41 - Selecionar perfil, L50 - Usuário|C08 - Selecionar Perfil|Gerencial, Desenvolvimento|
|  RF9   | O usuário deve poder controlar o volume de um título       |         US21          |L05 - Controlar, L50 - Usuário|C09 - Controlar volume|Gerencial, Desenvolvimento|
|  RF10  | O usuário deve poder cancelar sua assinatura               |         US05          |L02 - Assinatura, L50 - Usuário|C10 - Cancelar assinatura|Gerencial, Desenvolvimento|
|  RF11  | O usuário deve poder retomar um título                     |         US22          |L38 - Retomar, L49 - Título, L50 - Usuário|C11 - Controlar tempo de um título|Gerencial, Desenvolvimento|
|  RF12  | O usuário deve poder controlar o tempo de um título        |         US23          |L05 - Controlar, L11 - Duração, L49 - Título, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF13  | O usuário deve poder editar um perfil                      |         US12          |L12 - Editar Perfil, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF14  | O usuário deve poder ver informações da sua conta          |         US06          |L04 - Conta, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF15  | O usuário deve poder renovar sua assinatura                |         US07          |L02 - Assinatura, L35 - Renovar, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF16  | O usuário deve poder alterar a legenda                     |         US24	      |L23 - Legenda, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF17  | O usuário deve poder filtrar títulos                       |         US26          |L18 - Filtrar, L49 - Título, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF18  | O usuário deve poder baixar um título para assitir offline |         US25          |L03 - Assistir, L10 - Download, L49 - Título, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF19  | O usuário deve poder mudar dados de pagamento              |         US08          |L29 - Pagamento, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF20  | O usuário deve poder marcar títulos para assistir depois   |         US27          |L03 - Assistir, L49 - Título, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF21  | O usuário deve poder reproduzir automaticamente            |         US28          |L36 - Reprodução automática, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF22  | O usuário deve poder criar uma lista                       |         US14          |L06 - Criar, L24 - Lista, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF23  | O usuário deve poder alterar o idioma                      |         US29          |L05 - Controlar, L22 - Idioma, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF24  | O usuário deve poder pular a abertura                      |         US30          |L05 - Controlar, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF25  | O usuário deve poder trocar a qualidade da stream          |         US31          |L05 - Controlar, L45 - Streaming, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF26  | O usuário deve poder adicionar um título em uma lista      |         US15          |L24 - Lista, L49 - Título, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF27  | O usuário deve poder colocar um pin para acessar um perfil |         US13          |L01 - Acessar, L33 - Pin, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF28  | O usuário deve poder criar um perfil infantil              |         US16          |L06 - Criar, L31 - Perfil Infantil, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF29  | O usuário deve poder excluir um perfil                     |         US17          |L14 - Excluir, L30 - Perfil, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF30  | O usuário deve poder assistir um trailer                   |         US32          |L03 - Assistir, L16 - Extra, L48 - Trailer, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF31  | O usuário deve poder visualizar detalhes do título         |         US33          |L16 - Extra, L49 - Título, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF32  | O usuário deve poder sair de todos os dispositivos         |         US09          |L08 - Dispositivo, L39 - Sair, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF33  | O usuário deve poder assistir em segundo plano             |         US34          |L03 - Assistir, L40 - Segundo plano, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF34  | O usuário deve poder entrar em um grupo watch              |         US35          |L01 - Acessar, L21 - Grupo watch, L50 - Usuário| | Gerencial, Desenvolvimento|
|  RF35  | O usuário deve poder restringir a criação de perfis        |         US18          |L04 - Conta, L06 - Criar, L30 - Perfil, L50 - Usuário| | Gerencial, Desenvolvimento|

## 4. Referência bibliográfica
> - SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019.

## 5. Histórico de versão

| Versão | Data       | Descrição                         | Autor                   |
| ------ | ---------- | --------------------------------- | ----------------------- |
| 0.1    | 08/10/2021 | Criação do documento              | Juliana Valle           |
| 0.2    | 08/10/2021 | Descrição da introdução           | Vinícius Saturnino      |
| 0.3    | 08/10/2021 | Desenvolvimento do documento      | Juliana Valle           |
| 0.4    | 08/10/2021 | Terminando o corpo do documento   | Juliana Valle           |
| 0.4    | 08/10/2021 | Colocando referência bibliográfica| Juliana Valle           |


