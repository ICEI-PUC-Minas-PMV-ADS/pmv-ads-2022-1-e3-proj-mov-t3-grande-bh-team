## Plano de Teste de Software

Este documento descreve o plano para testar o protótipo de arquitetura do sistema. Este documento de Plano de Teste suporta os seguintes objetivos:
* Identificar informações existentes do projeto e o software que deve ser testado.
* Listar os requisitos de teste recomendados.
* Recomendar e descrever as estratégias de teste a serem empregadas.
* Identificar os recursos requeridos e fornecer uma estimativa dos esforços de teste.
* Listar os elementos de produto de trabalho das tarefas de teste.


Este Plano de Teste descreve os testes de integração e do sistema que serão conduzidos no protótipo de arquitetura após a integração dos subsistemas e componentes identificados no Plano de Integração da Construção para o Protótipo. É crítico que todas as interfaces do sistema e do subsistema sejam testadas, bem como o desempenho do sistema nesse estágio antecipado.

As interfaces entre os seguintes subsistemas serão testadas:

* Login 
* Cadastro Usuário
* Recuperação de senha
* Cadastro Pet
* Visitas dos perfis dos pets
* Candidatura de pedido de adoção
* Confirmação de adoção


As interfaces externas para os seguintes dispositivos serão testadas em:

* Computadores e smartphones locais


As medidas de desempenho mais críticas a testar são:

* Tempo de resposta para login remoto no sistema de registro em cursos.
* Tempo de resposta para acesso ao sistema de gerenciamento.
* Tempo de resposta do geral quando existem alguns acessos simultâneos ao banco de dados do gerenciamento de serviços.

# Teste de Integridade dos Dados e do Banco de Dados
A lista a seguir identifica os itens que foram identificados como alvos do teste. Essa lista representa o que será testado:

* Verificar acesso ao Banco de Dados com registros dos animais e dos usuários;
* Verificar a interrupção durante os processos de escolha dos animais e da candidatura para a adoção e demais registros.

# Teste de Interface com o Usuário

* Verificar a facilidade de navegação utilizando um conjunto de amostras de telas;
* Verificar se as telas de amostra estão em conformidade com os padrões de facilidade de uso.

# Teste de Desempenho

* Verificar o tempo de resposta para acesso ao sistema;
* Verificar o tempo de resposta para registros;
* Verificar o tempo de resposta para login remoto.

# Teste de Carga

* Verificar a resposta do sistema quando estiver carregado com alguns usuários com logon efetuado;
* Verificar a resposta do sistema quando existir diversos acessos simultâneos.

# Teste de Segurança e Controle de Acesso

* Verificar o Logon a partir de um aparelho mobile;
* Verificar a segurança de Logon por meio de mecanismos de nome de usuário e senha.

# Teste de Função

|Itens Plano de Teste| Conteúdo                                             |
|--|-------------------------------------------------------|
|1. Introdução| Principal objetivo de identificar acertos e possíveis manutenções e melhorias a serem feitas no sistema, o teste será feito com o usuário que se propõe a candidatar para adoção de um animal |
|2. Requisitos a serem testados| Login; Cadastro usuários; Recuperação de senha; Cadastro animais; Cadastro candidaturas; Permissão de candidaturas; Comunicação; Agendamento, recomendações sobre o pet e acompanhamento de datas; Logout     |
|3. Estratégias e ferramentas de teste| Será feito testes em diversos computadores locais e smartphones com diferentes usuários, ao menos 3        |
|4. Equipe e infra-estrutura| Equipe de desenvolvedores e testers é composta por: Gabriel - Desenvolvedor/Tester, Isaac - Desenvolvedor/Tester, Lucas - Desenvolvedor/Tester, Rafael - Desenvolvedor/Tester. Infraestrutura para testes: 4 desktops e 4 smartphones com acesso à aplicação        |
|5. Cronograma de atividades| Todos os testes serão realizados após a finalização do desenvolvimento da aplicação        |

# Teste da Interface com o Usuário

O teste da Interface com o Usuário verifica a interação de um usuário com o software. A meta do Teste de UI é assegurar que a Interface com o Usuário forneça ao usuário o acesso e a navegação adequados por meio das funções dos aplicativos. Além disso, o Teste de UI assegura que os objetos contidos na UI funcionem conforme esperado e estejam em conformidade com padrões corporativos ou do segmento de mercado.

|Objetivo do Teste| Verificar                                             |
|--|-------------------------------------------------------|
|Técnico| A navegação pelo aplicativo reflete os requisitos e funções de negócios, incluindo a navegação janela a janela, campo a campo e o uso de métodos de acesso; Objetos e características da aplicação, tais como menus, tamanho, posição, estado e foco estão em conformidade com os padrões; Criar / modificar testes para cada janela a fim de verificar a navegação adequada e os estados de objeto para cada janela e objeto do aplicativo. |
|Critérios de Conclusão| Verificação com êxito de cada janela permanecer consistente ou dentro do padrão aceitável |

