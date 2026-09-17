# DOCUMENTO DE ESCOPO - PROJETO: EsToDoList

**EsToDoList do Estudante**

A Planta Baixa do nosso ToDoList

1. **Objetivo do projeto:**

Ferramenta simples e focada nos estudantes para organizar tarefas, atividades de entrega, provas ou trabalhos de forma rápida e eficiente.

1. **Requisitos Funcionais (RF):**

RF01: No canto inferior direito possuirá um ícone com o símbolo “+”, e ao clicar o estudante poderá adicionar o que quiser. Ele deverá fornecer informações como nome da atividade, data de início, de entrega, descrição, o que será necessário para a atividade e o que precisa ser feito.

RF02: O usuário poderá clicar em uma tarefa já cadastrada e selecionar a opção de editar. Poderá alterar informações como nome, datas, descrição, materiais necessários e atividades que precisam ser realizadas.

RF03: O usuário apaga uma tarefa ao clicar em cima do tópico, no canto superior direito existirá uma lixeira, que ao clicar aparecerá a mensagem “Apagar atividade?” SIM ou NÃO. A tarefa será realmente excluída caso o usuário confirme.

RF04: No menu, onde irá aparecer todas as suas atividades, ao lado de cada seção vai ter o ícone “✔”, que ao ser clicado, ficará verde. A tarefa também poderá receber uma alteração visual, como texto riscado ou mudança de cor, para diferenciá-la das tarefas pendentes.

RF05: O usuário poderá pesquisar uma tarefa pelo nome utilizando uma barra de pesquisa. Também poderá filtrar as atividades por situação, como “Pendentes” e “Concluídas”, facilitando a localização de uma atividade específica.

1. **Requisitos não funcionais (RNF):**

RNF01: RESPONSIVIDADE - O sistema deverá funcionar corretamente em computadores, tablets e celulares, pois os estudantes podem acessar suas tarefas em diferentes dispositivos.

RNF02: DESEMPENHO - As páginas e funções principais deverão carregar rapidamente, pois o usuário não deve perder tempo esperando o sistema responder.

RNF03: USABILIDADE - A interface deverá ser simples, organizada e fácil de entender, pois o estudante precisa conseguir cadastrar e consultar suas atividades rapidamente.

4.**Fora Do Escopo:**

1. Notificações automáticas:

O sistema não terá notificações ou lembretes automáticos nessa primeira versão, porque o foco inicial será desenvolver as funções básicas de organização das tarefas.

  2. Integração com calendário

O sistema não será integrado a calendários externos, como Google Agenda, nesta primeira versão, pois isso aumentaria a complexidade do projeto e não é essencial para o funcionamento básico do ToDoList.

METODOLOGIA CASCATA:

| REQUISITOS | ANÁLISE E PROJETO | DESENVOLVIMENTO | TESTES | IMPLANTAÇÃO E MANUTENÇÃO |
| --- | --- | --- | --- | --- |
|   • Entrevistar alunos para entender como eles organizam suas tarefas  |   • Desenhar as telas do aplicativo no figma  |   • Escrever o código html da página principal |   • Verificar se o aplicativo funciona nos navegadores chrome e firefox |   • Corrigir um bug reportado por um usuário uma semana após o lançamento  |
|   • Escrever o documento de escopo com todas as suas funcionalidades |   • Definir a paleta de cores e a fonte que serão usadas no site  |   • Programar a função em javascript que salva uma nova tarefa no navegador  |   • Tentar “quebrar” campo em data, inserindo um texto em vez de um número |   • Publicar a versão final do site em um servidor online para que todos possam usar  |
|   • Analisar como outras ferramentas de organização de tarefas funcionam para identificar oportunidades de melhoria |   • Criar o diagrama de transição entre as telas para definir a jornada completa do usuário no aplicativo |   • Aplicar o design, as cores e as fontes definidas no Figma às páginas HTML |   • Verificar se o aplicativo ajusta o layout adequadamente em celulares e tablets |   • Vincular um endereço web próprio e garantir uma conexão segura aos usuários |
|   • Classificar os recursos entre essenciais para o lançamento inicial e secundários para futuras atualizações |   • Definir quais tabelas e campos (ex: título, data, status) serão necessários para armazenar os dados |   • Criar o repositório no GitHub para organizar as alterações de código e facilitar o trabalho em equipe |   • Testar o modal de exclusão de tarefas, confirmando se a exclusão é cancelada ao clicar em "NÃO" e concluída ao clicar em "SIM” |   • Criar um material de apoio simples para ensinar os novos alunos a utilizar as principais funções do aplicativo |

A MATRIZ DE RISCO:

| PROBA | ALTA | média | alta | alta |
| --- | --- | --- | --- | --- |
| BILI | MÉDIA | baixa | média | alta |
| DADE | BAIXA | baixa | baixa | média |
|  |  | ALTA | MÉDIA | BAIXA |
|  |  | IM | PAC | TO |

| Risco (descrição) | Probabilidade (baixa/alta) | Impacto (baixo/alto) | Plano de ação (o que faremos para prevenir ou remediar?)  |
| --- | --- | --- | --- |
| Ex: O único programador do projeto fica doente e se ausenta por uma semana. | Baixa  | Alto | Plano de ação: Manter toda a documentação do projeto atualizada e salva em um local compartilhado (como o notion), para que outra pessoa possa entender o andamento. |
|  |  |  |  |
| Risco 1: E se todo o código desenvolvido em uma aula fosse perdido porque ninguém fez o commit ou enviou o projeto para o GitHub | Baixa | Alto | Plano de ação: Crie o repositório no GitHub nos primeiros minutos de aula e adote pausas periódicas para salvar o progresso na nuvem. |
| Risco 2: Internet indisponível no momento de entrega/apresentação | Alta | Alto | Plano de ação: Rotear internet do próprio celular ou baixar o conteúdo no seu computador, ou em pendrives. |
| Risco 3: Durante o desenvolvimento do EsToDoList, os alunos que testaram o sistema gostaram da ideia e começaram a pedir um chat para conversar sobre as tarefas? | Alta | Baixo  | Plano de ação: Eu iria analisar onde estamos no projeto e ver se é possível fazer o chat ou não, e manteria o sistema simples e focado no objetivo principal, evitando essa complexidade técnica no meio do projeto.  |