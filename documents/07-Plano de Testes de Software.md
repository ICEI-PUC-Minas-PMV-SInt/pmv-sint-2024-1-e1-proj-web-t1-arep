# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Os testes funcionais serão realizados para simular o acesso ao site. Será testada a página de login de acesso do usuário, descrito no Caso de Teste CT-01. Nesse cenário, a página será testada por um dos membros da equipe. 

Os testes funcionais realizados no site estão descritos a seguir.
|Caso de Teste    | CT-1 - Tela de Login |
|:---|:---|
| Requisitos Associados | RF-02 O sistema deve possuir um sistema de cadastro / login<br>RF-24 O sistema deve conter a funcionalidade de recuperação de senha |
| Objetivo do Teste | Verificar se a autenticação do usuário ocorre adecuadamente. |
| Passos | <ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página de login.</li><li>Efetuar o login.</li><li>Acessar uma página autorizada. </li><li>Efetuar logoff.</li></Ol>|
| Critérios de êxito |<ul><li>A página de login precisa ser carregada corretamente.</li><li>Deve ocorrer a autenticação do usuário.</li><li>Após o login a página inicial        precisa ser carregada.</li><li>A página carregada deve ter acesso ao botão de logoff.</li><li>Após o logoff, a página de login deve ser carregada novamente.</li>   </ul>|  |

 |Caso de Teste|CT-2 Tela de Cadastro|
 |:---:|:---|
 |Requisitos associados|RF-05 O sistema deve possuir o cadastro de perfis de usuário<br>RF-11 Permitir que o usuário possa alterar suas informações pessoais na tela de perfil.|
 |Objetivo do teste|Verificar se o cadastro de usuários é realizado corretamente, garantindo o preenchimento de todos os campos obrigatórios de forma adequada."|
 |Passos|<ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página de login.</li><li>Efetuar o login.</li><li>Acessar a página de cadastro realizando conforme o uso destinado.</li><li>Efetuar o login corretamente.</li><li>Acessar a página inicial.</li><li>Garantir acesso a todo o conteúdo destinado, tanto para usuários quanto para fornecedores.</li><li>Efetuar o logoff.</li></ol>
 |Critérios de Êxito|<ul><li>Após o login, a página destinada ao uso específico do usuário será carregada automaticamente.</li><li>A página deve possibilitar a pesquisa ou anúncio.</li><li>A página carregada deve ter acesso ao botão de logoff.</li><li>Após o log out, a página de login deve ser novamente carregada.</li></ul>| 


   |Caso de Teste|CT-03 Tela de Anúncio |
   |:---:|:---|
   |Requisitos associados|RF-04 O cadastro de repúblicas deve permitir inserir a localização<br>RF-06 O sistema deve possuir um sistema de contato via formulário<br>RF-09 Permitir que o usuário comente em anúncios de república<br>RF-10 Permitir que o usuário avaliar a república<br>RF-14 Permitir que o usuário possa denunciar um anúncio de república. |
   |Objetivo do teste|Verificar se o sistema é de fácil acesso epara usuários leigos e de facil busca de repúblicas.|
   |Passos|<ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página inicial.</li><li>Acessar pagina de anúncio.</li><li> Acesso  ao formulario de contato.</li></ol>|
   |Critérios de Êxito|<ul><li>Após acessar, a página inicial de uso destinado deve ser carregada automaticamente.</li><li>A página deve exibir uma lista de repúblicas disponiveis, além de oferecer uma opção de busca rápida.</li><li>O banco de dados deve atualizar a disponibilidade das repúblicas automaticamente após alterções dos anunciantes..</li></ul>|

 |Caso de Teste|CT-04 Tela Anunciar |
   |:---:|:---|
   |Requisitos associados|RF-01 O sistema deve possibilitar o cadastro de repúblicas<br>RF-03 O cadastro de repúblicas deve possuir um sistema de filtros, fotos e descrição<br>RF-04 O cadastro de repúblicas deve permitir inserir a localização<br[RF-15 Permitir que o usuário possa publicar fotos da república|
   |Objetivo do teste|Verificar se o sistema direciona corretamente o usuário para a função apropriada.|
   |Passos|<ol><li>Acessar o navegador.</li><li>Informar o endereço do site.</li><li>Visualizar a página de login.</li><li>Efetuar o login.</li><li>Acessar a página inicial correspondente à sua função de uso.</li><li>Preencher informações da república disponivel.</li><li>Subir fotos das repúblicas</li><li>Expecificar o perfil de moradores aceitos na republica.</li><li>Efetuar logoff.</li></ol>|
   |Critérios de Êxito|<ul><li>Após o login a página inicial correspondente precisa ser carregada.</li><li>A página deve exibir uma tela de anúcio com opção de adicionar uma nova república.</li><li>A área do usuário deve possibilitar a alteração dos dados e localização para verificar a região pertencente da república.</li><li>A página carregada deve ter sempre acesso ao botão de log out.</li><li>Após o log out, a página de login deve ser novamente carregada.</li></ul>|
   
 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)
