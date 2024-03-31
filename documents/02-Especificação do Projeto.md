# Especificação do Projeto

## Perfis de Usuários

[Enumere e faça o detalhamento dos perfis de usuários. Utilize o modelo de tabela abaixo para sintetizá-los.]

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil Nome </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">...</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>...</td>
</tr>
</tbody>
</table>


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

