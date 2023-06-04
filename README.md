<span id="topo">

<h1 align="center">Sprint 4: 15/05/2023 a 04/06/2023</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Para esta última sprint foi acordado a entrega final tanto do aplicativo móvel quanto da dashboard web, dessa forma o time como um todo aplicou esforços para implementar melhorias no que já estava concluído e integrar novas funcionalidades como a gestão de permissões dos usuários (promoção ou rebaixamento de nível entre administrador e visitante), filtragem de parcerias por status e as análises dos dados na web.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:
- :heavy_check_mark: **RF 02:** Dashboard para análises
- :heavy_check_mark: **RF 04:** CRUD de usuários
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das regras de negócio do cliente
- :heavy_check_mark: **RNF 09, 10 e 11:** Utilização de TypeScript, React Native e React

<span id="entregas">
        
## 📲 Entregas
Para as entregas da sprint o combinado foi a dashboard web com as análises dos dados disponíveis e o aplicativo completo e revisado (com todos os requisitos levantados para o projeto).
    
### RF 02: Dashboard para análises
    
Finalizando a parte web do projeto, foi desenvolvida uma dashboard com a análise dos dados disponíveis, como o acordado com o cliente, apresentando alguns totalizadores, listas e gráficos, como o demonstrado abaixo:

### RF 04: CRUD de usuários

Finalizando todas as etapas da gestão de usuários, agora é possível promover ou rebaixar os níveis de permissão de cada usuário, que por padrão são cadastrados como "visitantes" mas podem ser promovidos a "administrador" por um administrador já cadastrado na plataforma.

### RNF 08: Documentação no GitHub com mapeamento das regras de negócio do cliente

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/owl-partners-documentation).

### RNF 09, 10 e 11: Utilização de TypeScript, React Native e React

Estes requisitos não funcionais se tratam da utilização das tecnologias TypeScript, React Native e React, que foi satisfeita também nesta sprint com o uso do TypeScript no frontend, mobile e backend, mas também com o uso do React no frontend e do React Native no mobile.

→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre mobile, web e backend, onde o mobile se responsabilizou pelo gerenciamento das permissões dos usuários e filtragem de parcerias, além da implementação de melhorias, enquanto o time web se focou na integração da dashboard e o backend criou o endpoint para filtragem de parcerias e aplicou melhorias no código. 
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:

<div align="center">
   <img src="https://github.com/The-Bugger-Ducks/owl-partners-documentation/assets/79321198/1cbbaf3b-1de8-4120-8ea7-f85e0fad4e6d" alt="Gráfico do Burndown">

</div>

<span id="links">
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 4ª sprint:
  - Repositório do app: [clique aqui para acessar "owl-partners-mobile"](https://github.com/The-Bugger-Ducks/owl-partners-mobile)
  - Repositório da dashboard: [clique aqui para acessar "owl-partners-web"](https://github.com/The-Bugger-Ducks/owl-partners-web)
  - Repositório da API: [clique aqui para acessar "owl-partners-back"](https://github.com/The-Bugger-Ducks/owl-partners-back)

→ [Voltar ao topo](#topo)
