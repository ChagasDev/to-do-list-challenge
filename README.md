# Lets Code - Módulo 5: JS Vanilla - Matheus Silva Chagas
# <i>To-do-list challenge</i>

## Proposta de Teste

Criar uma to-do list que consiste em adicionar elementos a uma lista e poder marca-los como feito ou não

## Requisitos Obrigatórios

- Utilizar JS, HTML e CSS puro, ou seja sem qualquer tipo de biblioteca ou framework
- A solução deve apresentar um campo para inserir o nome da tarefa a ser feita e um botao para adicionar a tarefa a lista
- Ao adicionar uma nova tarefa esperar 2 segundos para que seja exibido na lista de tarefas.
- Ao adicionar uma nova tarefa ela deverá vir por padrão no estado de a fazer
- A solução deve apresentar uma lista para listar as tarefas
- Cada elemento da lista deverá apresentar 2 estados diferentes, um pra item a se fazer e um para item feito e tem que ter uma diferença visual entre eles
- Ao clicar no item da lista o mesmo deve mudar se estado, feito -> a fazer ou a fazer -> feito
- Deve ser possível armazenar quantos items o usuario quiser a lista
- A lista deve ser armazenada de uma forma que se o usuario entrar novamente na pagina ele poderá ver todos os itens ja cadastrados e seus respectivos estados (único que não consegui cumprir) 
- Criar uma boa documentação para a solução (README).


## Requisitos Opcionais (Plus)

- Implementar uma solução otimizada
- Em cada elemento da lista apresentar um botao de deletar e caso o usuario aperte esse botao o item some da lista
- Implementar uma boa interface gráfica para a solução
- Publicar a aplicação em algum ambiente (GitHub Pages,...)
- caso o aluno queira implementar mais alguma funcionalidade fique a vontade, mas deixe explicado no README


## Entrega

A entrega deverá ser feita ate o dia 28/02/2022

Para a entrega o aluno deverá criar um pull request(PR) para esse repositório.


## Observações

- Não será aceito trabalhos após essa data
- Se o sistema não rodar o aluno ficará com a nota 0
- Não será permitido copias e se isso for detectado os alunos envolvidos ficarão com a nota 0

## Ferramentas que foram utilizadas para elaboração dá pagina: 
 
 - addEventListener -> Para "escutar" o que foi feito
 - SetTimeout -> para o delay de 2 segundos 
 - LocalStorage -> Para armazenamento
 - parentELement
 - toggle (css)

## Estrutura do código 

- A estrutura do código é feitar por 3 arquivos, um html, um css e um Javascript. 
- No html estão o input para colocação das novas tarefas bem como o botão de adicionar nova tarefa. 
- No css, por sua vez, está a estilização utlizada na pagina. Melhorias ocorrerão posteriormente.
- No Javascript, está a parte de interação e comportamento da pagina. Formada em sua maioria por funções para cada evento que o usuario quiser. Exemplo: Adicionar uma tarefa, armazenar os dados no LocalStorage, lista-la como feita e criação de div dinâmica para a lista de tarefas.

## OBS: 
Não cumpri um requisito obrigatorio que foi o de atualização da pagina e os dados continuarem na pagina para o usuário. 

## Aluno:
- Matheus Silva Chagas





