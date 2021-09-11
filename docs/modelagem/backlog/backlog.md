# Backlog

## 1. Introdução
&emsp;&emsp;O Backlog do Produto é uma lista priorizada de itens sobre os quais o Time de Desenvolvimento trabalhará no decorrer do projeto. Trata-se da lista de funcionalidades e requisitos que deverão ser entregues ao cliente ao longo das Sprints. Ele é atualizado, reordenado e refinado de acordo com o nível de detalhes que é possível de se ter em cada momento do projeto. A equipe de desenvolvimento não trabalha no backlog no ritmo do proprietário do produto, e o proprietário do produto não encaminha trabalho para a equipe de desenvolvimento. Em vez disso, a equipe de desenvolvimento pega o trabalho do backlog do produto de acordo com sua capacidade, em ritmo contínuo (Kanban) ou por iteração (Scrum). 

## 2. Épicos
&emsp;&emsp;Épico pode ser descrito como uma história de usuário que ainda não foi detalhada, é muito grande ou ainda possui muita incerteza e portanto não pode ser transformada em incremento do produto. O épico deve ser fatiado em histórias de usuário menores. Nesse projeto os épicos foram separados em:
\
- [Conta](ep01_conta.md)\
- [Perfil](ep02_perfil.md)\
- [Conteúdo](ep03_conteudo.md)\

## 3. Histórias de Usuários
&emsp;&emsp;Em Agile, uma história de usuário é uma descrição curta, informal e em linguagem simples do que um usuário quer fazer dentro de um produto de software para obter algo que ele considere valioso.
As histórias de usuários normalmente seguem o padrão de papel-função-benefício (ou modelo):\
- Eu, como um usuário, gostaria de < OBJETIVO >, para poder < UMA RAZÃO >
### EP01: Conta

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... |               Para poder...               | Prioridade |
| :-----------------: | :-------------: | :-----------------------------: | :---------------------------------------: | :--------: |
|        US01         |       RF3       |         Criar uma conta         |           Ter acesso ao sistema           |    Must    |
|        US02         |       RF2       |         Realizar login          |     Acessar o conteúdo da plataforma      |    Must    |
|        US03         |       RF5       |         Realizar logout         |  Desconectar minha conta do dispositivo   |    Must    |
|        US04         |       RF7       |      Recuperar minha senha      |          Ter acesso a plataforma          |    Must    |
|        US05         |      RF10       |    Cancelar minha assinatura    |      Não precisar pagar mensalidade       |    Must    |
|        US06         |      RF14       | Ver informações da minha conta  |           Verificar meus dados            |    Must    |
|        US07         |      RF15       |    Renovar minha assinatura     |   Ter acesso ao conteúdo da plataforma    |    Must    |
|        US08         |      RF19       |    Mudar método de pagamento    |           Continuar assinatura            |   Should   |
|        US09         |      RF32       |  Sair de todos os dispositivos  | Controlar quem está acessando minha conta |   Could    |

### EP02: Perfil

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... |                    Para poder...                    | Prioridade |
| :-----------------: | :-------------: | :-----------------------------: | :-------------------------------------------------: | :--------: |
|        US10         |       RF1       |          Criar perfis           |    Separar minhas preferências dos demais perfis    |    Must    |
|        US11         |       RF8       |      Selecionar um perfil       | Ter acesso as preferências de um determinado perfil |    Must    |
|        US12         |      RF13       |        Editar um perfil         |   Alterar as informações de um determinado perfil   |    Must    |
|        US13         |      RF27       |         Definir um pin          |            Proteger o acesso a um perfil            |   Could    |
|        US14         |      RF22       |         Criar uma lista         |        Salvar conteúdos de minha preferência        |   Should   |
|        US15         |      RF26       |  Adicionar título à uma lista   |     Salvar um determinado título na minha lista     |   Could    |
|        US16         |      RF28       |      Criar perfis infantis      |    Filtrar os conteúdos por classificação etária    |   Could    |
|        US17         |      RF29       |        Excluir um perfil        |          Remover um perfil da minha conta           |    Must    |
|        US18         |      RF35       |  Controlar a criação de perfis  |           Restringir a criação de perfis            |   Could    |

### EP03: Conteúdo

| História de Usuário | Rastreabilidade |    Eu, como usuário gostaria de...    |                                  Para poder...                                   | Prioridade |
| :-----------------: | :-------------: | :-----------------------------------: | :------------------------------------------------------------------------------: | :--------: |
|        US19         |       RF4       |           Assistir títulos            |                         Consumir conteúdo da plataforma                          |    Must    |
|        US20         |       RF6       |           Pesquisar Títulos           |                       Procurar por um contéudo específico                        |    Must    |
|        US21         |       RF9       |             Mudar volume              |                      Assistir o conteúdo com o volume ideal                      |    Must    |
|        US22         |      RF11       |         Retomar algum título          |                Continuar assistindo um conteúdo que não terminei                 |    Must    |
|        US23         |      RF12       |     Controlar tempo de um título      |                    Assistir a partir de um determinado ponto                     |    Must    |
|        US24         |      RF16       |   Alterar configurações da legenda    |            Assistir conteúdos em um idioma que eu não tenha fluência             |    Must    |
|        US25         |      RF17       |           Baixar um título            |                            Assistir de forma offline                             |   Should   |
|        US26         |      RF18       |            Filtrar títulos            |                       Procurar por um contéudo específico                        |   Should   |
|        US27         |      RF20       | Marcar um título para assistir depois |            Evitar que me esqueça de assistir um determinado conteúdo             |   Should   |
|        US28         |      RF21       |     Definir reprodução automática     |       Assistir conteúdo em série sem precisar ficar alternando manualmente       |   Should   |
|        US29         |      RF23       |      Alterar idioma de um título      |                 Consumir o conteúdo em um idioma de preferência                  |   Should   |
|        US30         |      RF24       |      Pular abertura de um título      |        Não precisar assistir abertura repetidamente de conteúdos em série        |   Should   |
|        US31         |      RF25       |       Mudar qualidade de stream       | Consumir o conteúdo na qualidade desejada e poder controlar o consumo de conexão |   Could    |
|        US32         |      RF30       |          Assistir um trailer          |                     Ter uma prévia do conteúdo de um título                      |   Could    |
|        US33         |      RF31       |   Visualizar detalhes de um título    |                     Ter uma prévia do conteúdo de um título                      |   Should   |
|        US34         |      RF33       |  Assistir conteúdo em segundo plano   |                Consumir o conteúdo enquanto realizo outra tarefa                 |   Could    |
|        US35         |      RF34       |       Entrar em um Group Watch        |             Assistir a um título simultaneamente com outras pessoas              |   Could    |

## 4. Bibliografia

>- WIEGERS, Karl; BEATTY, Joy. "Software Requirements". Microsoft Press, 2013.
>- FERREIRA, Avelino. Product Backlog: Épico, História de Usuário e Tarefas. K21, 2020. Disponível em: https://k21.global/blog/product-backlog-epico-historia-tarefas. Acesso em: 10 de Setembro de 2021.
>- RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva.  Atlassian. Disponível em: https://www.atlassian.com/br/agile/scrum/backlogs. Acesso em: 10 de Setembro de 2021.

## 5. Histórico de versão

| Versão | Data       | Descrição                        | Autor        |
| ------ | ---------- | -------------------------------- | ------------ |
| 0.1    | 10/09/2021 | Criação das Histórias de Usuário | Paulo Victor |
| 0.2    | 10/09/2021 | Adição da introdução, descrição sobre épicos e histórias de usuário e bibliografia | Thiago Mesquita |
