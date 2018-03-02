1. Descrição geral do sistema
O sistema PointStore funciona em  multiplataforma, ou seja tanto via web quanto no seu smartphone,  trabalha no comércio de pontos de vantagem entre usuários, é a melhor forma para você utilizar seus pontos seja vendendo para outros usuários ou comprando para resgatar os pontos referente a  empresa que fornece os pontos de vantagem. 
2. Requisitos funcionais
      1.  [RF001] Cadastrar Usuário
Descrição do caso de uso: O caso de uso se inicia quando o usuário preenche todos os campos e encerra clicando no botão de cadastrar.


Entradas e pré-condições: Não tem.


Saídas e pós-condição: Os dados são cadastro no banco de dados e retorna com um aviso ao usuário que foi cadastrado com sucesso.


      1.  [RF002] Atualizar Senha
Descrição do caso de uso: o usuário faz uma solicitação na atualização da senha


Fluxo Básico: 
Passo 1: O caso de uso se inicia quando o usuário clica no botão alterar senha na tela de login do sistema
Passo 2: o usuário digita o email e senha
Passo 3: o usuário submete as informações
Passo 4: se as informações estiverem corretas a senha será alterada e retornará uma mensagem informando que foi atualizada com sucesso, o caso de uso termina.


Fluxo Alternativo 1:
Passo 1 : esse fluxo se inicia no Passo 4 do fluxo básico, quando o sistema detecta que as informações incorretas 
Passo 2: o sistema pede ao usuário que ele insira o email e senha novamente
Passo 3: o sistema continua a partir do passo 4.


Entradas e pré-condições: Recebe como entrada o email e senha


Saídas e pós-condição: O usuário consegue atualizar a senha.


      1. [RF003] Logar Usuário
Descrição do caso de uso:  preenche os campos de login e senha.


Entradas e pré-condições: Recebe como entrada o login e senha.


Saídas e pós-condição: Retorna uma mensagem informando ao usuário que a alteração foi concluída.
      1. [RF004] Atualizar Perfil do Usuário
Descrição do caso de uso: O caso de uso se inicia quando o usuário acessa pelo link o perfil e altera as informações.


Entradas e pré-condições: Recebe como entrada os dados que deseja alterar, e tem como pré-condição estar logado no sistema.


Saídas e pós-condição: Retorna uma mensagem informando ao usuário que a alteração foi concluída.


3. Requisitos não-funcionais
      1. [NF001] Sistema Web responsivo
O sistema terá uma interface amigável ao usuário independente de onde ele esteja utilizando, seja no Desktop ou mobile utilizando bootstrap.


      1. [NF002] Sistema Mobile Android 5.1+
Embora não seja um requisito essencial ao sistema, deve ser considerada por corresponder a um fator de qualidade de software, sistema deve funcionar do Android 5.1 até o mais atual.


      1.  [NF003] Obrigatoriamente Banco de dados relacional Mysql
Utilizar a tecnologia MySQL para manter os dados do sistema.


      1.  [NF004] Arquitetura de software utilizando SPA- Single Page Application
Padrão de aplicações que carregam apenas uma página e atualizar dinamicamente as informações exibidas à medida que o usuário interage com a aplicação.
      1.  [NF005] Utilização de Serviço REST


Padrão arquitetural usado em serviços Web
