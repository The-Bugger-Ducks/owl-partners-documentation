<span id="topo">

<h1 align="center">Sprint 3: 24/04/2023 a 14/05/2023</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Para esta 3ª sprint o foco do desenvolvimento foi em melhorias do aplicativo além da implementação de CRUD de usuários e finalização do login/logout no app. Já em questão da web, temos o início dos endpoints que serão consumidos na dashboard e a implementação de autenticação.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 05:** Login e logout do sistema
- :heavy_check_mark: **RF 04:** CRUD de usuários
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das regras de negócio do cliente
- :heavy_check_mark: **RNF 11:** Utilização de React

<span id="entregas">
        
## 📲 Entregas
Para as entregas da sprint foi acordado o início do desenvolvimento do dashboard web juntamente com o gerenciamento de usuários no aplicativo móvel (o CRUD completo exceto gerenciamento de permissões).
    
### RF 05: Login e logout do sistema
    
Completando o fluxo de usuários no aplicativo, agora é possível fazer login e logout no sistema, além de ter a criação de contas por parte dos usuários (que sempre serão cadastrados por padrão como visitantes e depois podem ser alterados para administradores).

### RF 04: CRUD de usuários

Continuando a questão do fluxo de usuários no aplicativo, foi adicionado a listagem, edição e exclusão de usuários, além da possibilidade de criar uma conta própria (por padrão do tipo "visitante").

<details>
   <summary>Demonstração do <b>cadastro de usuários</b></summary> <br>
  
   https://github.com/The-Bugger-Ducks/owl-partners-mobile/assets/80930525/1bada4de-c491-402c-bf67-54e577c08c92
</details>
<details>
   <summary>Demonstração da <b>exclusão de usuárioso</b></summary> <br>
  
   https://github.com/The-Bugger-Ducks/owl-partners-mobile/assets/80930525/292c5ea7-3ce8-4d7b-9d42-08c91a6b358b
</details>
<details>
   <summary>Demonstração da <b>edição de usuários</b></summary> <br>
  
   https://github.com/The-Bugger-Ducks/owl-partners-mobile/assets/80930525/09b664be-c699-48fa-bd58-3f63f232f174
</details>
<details>
   <summary>Demonstração da <b>edição de senha e login</b></summary> <br>
  
   https://github.com/The-Bugger-Ducks/owl-partners-mobile/assets/80930525/11784516-2046-4e3d-b9ad-27152e280ddb
</details>

    
### RNF 08: Documentação no GitHub com mapeamento das regras de negócio do cliente

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/owl-partners-documentation).

### RNF 11: Utilzação de React

Este requisito não funcional se trata da utilização de React, que foi satisfeito nesta sprint pois a tecnologia foi utilizada no desenvolvimento da dashboard web.

→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre mobile, web e backend, onde o mobile se responsabilizou pelo gerenciamento de usuários e implementação de melhorias, enquanto o time web se focou na estruturação da dashboard e o backend criou o serviço que popularia esta dashboad. 
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:

<div align="center">
    
   <img src="https://github.com/The-Bugger-Ducks/owl-partners-documentation/assets/79321198/85a9098a-7ec7-42b0-a01e-24a1c121f9cb" alt="Gráfico do Burndown">
    
</div>

<span id="links">
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 3ª sprint:
  - Repositório do app: [clique aqui para acessar "owl-partners-mobile"](https://github.com/The-Bugger-Ducks/owl-partners-mobile)
  - Repositório da API: [clique aqui para acessar "owl-partners-back"](https://github.com/The-Bugger-Ducks/owl-partners-back)

→ [Voltar ao topo](#topo)
