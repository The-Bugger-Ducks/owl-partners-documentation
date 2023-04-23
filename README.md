<span id="topo">

<h1 align="center">Sprint 2: 04/04/2023 a 23/04/2023</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Dando continuidade para no desenvolvimento de um aplicativo para gerenciamento de parcerias, nesta segunda sprint o time se focou em funcionalidades que envolvem o agendamento de reuniões (seu CRUD completo) bem como trabalhos de refatoração, aplicando padrões e boas práticas, além de continar o fluxo de usuários (com sua listagem, criação, edição, login e logout), além de login de usuários.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 06:** CRUD de reuniões
- :heavy_check_mark: **RF 07:** Criação, edição e leitura de comentários de anotação de reuniões
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das regras de negócio do cliente
- :heavy_check_mark: **RNF 09:** Utilização de TypeScript
- :heavy_check_mark: **RNF 10:** Utilização de React Native

<span id="entregas">
        
## 📲 Entregas
Para entregas da sprint foi garantido o desenvolvimento do CRUD de reuniões, juntamente com a manipulação das anotações de reunião, além do fluxo de usuários, com sua listagem, criação, edição, exclusão, login e logout. Segue um vídeo demonstrativo das entregas da sprint:

<div align="center">

https://user-images.githubusercontent.com/69374340/233815050-5723ad3a-f3d2-42a0-b9b5-65539799b5d6.mp4   

</div>

### RF 06: CRUD de reuniões

Este requisito funcional diz respeito às ações de criação, listagem, edição e exclusão de reuniões, onde é possível observar tais funcionalidades na tela inicial, com as listagens de "próximas reuniões" e "últimas reuniões", ou nos detalhes de uma parceria, mais precisamente no histórico, na aba de reuniões. Ao acessar uma reunião é possível conferir seus dados, como parceria, data, horário e tema, além de poder ver e cadastrar anotações, como nas demonstrações abaixo:

<div align="center">

https://user-images.githubusercontent.com/69374340/233813651-c5be575e-fa14-4b31-ac89-c009b3c15fcd.mp4
    
</div>

### RF 07: Criação, edição e leitura de comentários de anotação de reuniões

Este requisito funcional se trata da criação, edição e listagens de anotações de uma reunião, onde se pode acessar ao selecionar uma reunião na tela inicial ou selecionar uma reunião dentro da tela de detalhes de parceria. Na tela dos detalhes da reunião é possível ver a listagem de anotações, quando existentes, bem como a criação de novas anotações e edição das mesmas, como o demonstrado a seguir:

<div align="center">

https://user-images.githubusercontent.com/69374340/233814140-3a878559-74a0-49ad-9f2c-a6b58b643219.mp4
    
</div>

### RNF 08: Documentação no GitHub com mapeamento das regras de negócio do cliente

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/owl-partners-documentation).

### RNF 09: Utilzação de TypeScript & RNF 10: Utilização de React Native

Este requisito não funcional se trata da utilização de Typescript e React Native, que foi satisfeito ainda nesta sprint, dado que tanto no servidor, feito com Node, foi utilizado o Typescript quanto no aplicativo mobile, feito com Expo e React Native.

→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre mobile e backend, onde o mobile se responsabilizou pela da interface e integrações das funcionalidades e o backend pela estruturação das rotas a serem consumidas. 
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:
    
<div align="center">

<img src=https://user-images.githubusercontent.com/79321198/233816213-1eedd109-98f4-4a8f-91c1-b186505dfbb4.png>
    
</div>

<span id="links">
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 2ª sprint:
  - Repositório do app: [clique aqui para acessar "owl-partners-mobile"](https://github.com/The-Bugger-Ducks/owl-partners-mobile)
  - Repositório da API: [clique aqui para acessar "owl-partners-back"](https://github.com/The-Bugger-Ducks/owl-partners-back)

→ [Voltar ao topo](#topo)
