# Especificação do Projeto

## Personas

<table>
<tr>
   <th>Foto</th>
    <th>Nome</th>
    <th>Descrição</th>
    <th>Aplicativos</th>
    <th>Motivações</th>
    <th>Frustrações</th>
    <th>Hobbies, História</th>
  
</tr
        <tr>
    <td><img title="João Marcos" src="https://this-person-does-not-exist.com/img/avatar-gen8bd66d54ec14bb933aac73bae177515e.jpg"/></td>
    <td>João Marcos </td>
    <td>
      <ul>
        <li>45 anos</li>
        <li>Motorista de Uber</li>
        <li>Mora em SP junto com seus dois filhos </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Uber</li>
        <li>Instagram</li>
        <li>WhatsApp</li>
        <li>ifood</li>
         </ul>
    </td>
    <td>
      <ul>
        <li>Dar estudo aos filhos</li>
        <li>Ter um financeiro estável</li>
        <li>Dar boas experiências aos filhos</li>
      </ul>
    </td>
    <td>
      <li>Perdeu a esposa</li>
      <li>Tem dificuldade em sustentar os filhos</li>
    </td>
    <td>
      <li>Cozinhar para filhos e amigos</li>
      <li>Conhecer lugares novos</li>
       <li>Perdeu a esposa tem 2 anos, então passou a cuidar dos filhos sozinho, lutando para dar a eles o melhor. </li>
          </td>
</tr
        <tr>
    <td><img title="Ana Julia" src="https://this-person-does-not-exist.com/img/avatar-gen0b767dea65368b9a19b3a2c1b1618306.jpg"/></td>
    <td>Ana Julia </td>
    <td>
      <ul>
        <li>28 anos</li>
        <li>Casada</li>
        <li>1 filho de 10 anos
        <li>Trabalha em home office </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Ifood</li>
        <li>Instagram</li>
        <li>WhatsApp</li>
        <li>Facebook</li>
         </ul>
    </td>
    <td>
      <ul>
        <li>Ter mais tempo para passar com o filho e marido</li>
        <li>Dar o melhor a seu filho</li>
      </ul>
    </td>
    <td>
      <li>Dificuldade em organizar uma rotina em casa</li>
    </td>
    <td>
      <li>Viajar, conhecer novas culturas</li>
      <li>Testar pratos novos na cozinha</li>
       <li>Começou a trabalhar de casa para poder ficar mais perto do filho, porém as demandas estão altas. </li>
          </td>
          </tr
        <tr>
    <td><img title="Maria Carla" src="https://this-person-does-not-exist.com/img/avatar-gende601983b4e1674ea10af620aab5b3fb.jpg"/></td>
    <td>Maria Carla </td>
    <td>
      <ul>
        <li>35 anos</li>
        <li>Casada</li>
        <li>Mãe de 2 meninas</li>
        <li>Trabalha como Assistente Admnistrativo</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>WhatsApp</li>
        <li>Shopee</li>
        <li>Ifood</li>
         </ul>
    </td>
    <td>
      <ul>
        <li>Passar tempo com as filhas </li>
        <li>Ter uma vida estável</li>
      </ul>
    </td>
    <td>
      <li>Não conseguiu fazer graduação</li>
    </td>
    <td>
      <li>Conhecer pessoas e lugares novos</li>
      <li>Cozinhar para a família</li>
       <li>Teve as filhas muito cedo e hoje trabalha para poder dar um futuro melhor para as filhas. </li>
          </td>


## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.

|EU COMO `PERSONA`   | QUERO/PRECISO `O QUE` |PARA ... `POR QUE`             |
|--------------------|---------------------------|----------------------------------|
| Ana Julia | ter minhas receitas de culinária em um único lugar | deixar de me sentir perdida na hora de procurar uma receita |
| Ana Julia | ver receitas de acordo com meu gosto e preferências | economizar tempo procurando receitas que satisfaçam meus gostos e restrições |
| Maria Carla | saber o que outras pessoas estão achando daquela receita | matar curiosidade em saber o que outras pessoas acharam da receita, se tiveram opinião em comum, ver repercussão |
| João Marcos | ver sugestões de receitas de acordo com meu horário atual | sair do excesso de informação, ter mais praticidade e economizar tempo |
| Maria Carla | salvar minhas receitas favoritas | poder encontrar rapidamente minhas receitas favoritas |
| Maria Carla | ver receitas tanto no computador quanto no celular | quando tiver na casa dos meus parentes e quiser mostrar uma receita para eles, ou para prepararmos juntos |

## Requisitos do Projeto

### Requisitos Funcionais

[Utilize o modelo de tabela abaixo para apresentar os requisitos funcionais]

|ID      | Descrição                | Prioridade |
|--------|---------------------------------|----|
| RF-01  |  O sistema deve possuir um mecanismo de cadastro e login | ALTA  | 
| RF-02  |  O sistema deve possibilitar o cadastro e login rápido com conta do Google | ALTA  |
| RF-03  |  O sistema deve ter a funcionalidade de perfil e de personalização do mesmo, definindo preferências | ALTA  |
| RF-04  |  O sistema deve ter uma função do usuário cadastrado adicionar uma nova receita à plataforma | ALTA  |
| RF-05  |  O sistema deve ter uma função de adicionar foto e descrição na publicação de receitas | ALTA  |
| RF-06  |  O sistema deve ter um sistema de aprovação de publicações de receita pelos usuários, usando um algoritmo para identificar se a publicação tem um formato de receita ou se o usuário criou uma publicação fora de contexto | ALTA  |
| RF-07  |  O sistema deve permitir que usuários tenham um filtro de pesquisa, para pesquisar cada receita por nomes ou categorias | ALTA  |
| RF-08  |  O sistema deve possibilitar um sistema de interação entre usuários, com compartilhamento, comentários e feedbacks para as receitas | MÉDIA |
| RF-09  |  O sistema deve possibilitar o compartilhamento externo das receitas através de um link | MÉDIA |
| RF-10  |  O sistema deve conter um atalho de compartilhamento direto no Facebook ou WhatsApp | MÉDIA |
| RF-11  |  O sistema deve ter uma função de salvar as receitas | ALTA  |
| RF-12  |  O sistema deve ter uma função de ver as receitas salvas | ALTA  |
| RF-13  |  O sistema deve ter um algoritimo de recomendação com base no que cada cliente pesquisa com frequência | MÉDIA |
| RF-14  |  O sistema deve conter um mecanismo de tags, para facilitar as buscas | BAIXA |
| RF-15  |  O sistema deve ter uma pré apresentação da receita passando pelo feed | MÉDIA |

**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |  O sistema deve ser capaz de carregar as páginas de receitas em menos de 3 segundos, para garantir uma experiência de usuário rápida.  | ALTA | 
| RNF-02 |  O sistema deve suportar simultaneamente pelo menos 1000 usuários ativos sem degradação significativa no desempenho.  | MÉDIA | 
| RNF-03 |  O sistema deve ser facilmente escalável para acomodar um aumento de 50% no número de usuários sem a necessidade de alterações significativas na infraestrutura.  | MÉDIA |
| RNF-04 |  O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge).  | ALTA |
| RNF-05 |  O site deverá ser responsivo permitindo a visualização em um celular de forma adequada.  | ALTA |

**Prioridade: Alta / Média / Baixa. 

### Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID     | Descrição                |
|-------|---------------------------------|
| RF-01 | O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 26/06/2024. |
| RF-02 | O aplicativo deve se restringir às tecnologias básicas da Web no Front-end |
| RF-03 | A equipe não pode subcontratar o desenvolvimento do trabalho. |
| RF-04 | A plataforma permitirá cadastro apenas de pessoas do Brasil. |
| RF-05 | O idioma da plataforma será apenas PT-BR. |
| RF-06 | O projeto deverá ser realizado somente com ferramentas gratuitas. |

