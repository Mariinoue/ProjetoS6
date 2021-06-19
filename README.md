# On11-TodasEmTech-s6-Introducao-Node
Turma Online 11 - Todas em Tech | Back-end | 2021 | Introdução à API:
HTTP e NodeJS

## Para o lar
Abra o PullRequest Respondendo as seguintes questões:

1) Qual a relação entre os métodos HTTP e o CRUD?
    
    HTTP são usados para manipular recursos
    O metodos HTTP são usados pelo REST API.
    Os metodos de requisição mais comuns do HTTP são: 
        - GET -solicita representação de um recurso especifico. 
        - PUT -usado quando se deseja criar ou trocar um recurso.
        - POST -quando se quer criar um novo recurso no servidor.
        - DELETE -quando se deseja apagar um recurso no servidor.
    
    CRUD fazem 4 operações básicas, que são realizadas a nível dos bancos de dados.
    CRUD é um acronimo de:
        - Create
        - Read
        - Update
        - Delete

    As funcionabildades são parecidas, mas atuam em partes diferentes. CRUD está vinculado ao banco de dados.
    REST é utilizado para desenvolver web API para suportar o aplicativo e suas funcionabilidades. 

    Exemplo: 
    - Site do Photoshop. 
    - Você entra no site e procura o pacote illustrator. 
    - O site vai fazer um Request com GET até o Serviço de Informação
    - E a partir desse ponto o READ entra em ação
    - Entrando em contado com o banco de dados 
    - Busca a informação e retorna para o serviço de informação
    - O GET recebe a informação 
    - E você recebe a informação sobre o pacote Illustrator

    REST atua como uma interface para CRUD que acessa o banco de dados e executa uma ação. Como recuperar dados. 


2) Comente, com exemplos, a diferença entre o PUT e o PATCH.

    Put é um metodo que altera toda infromação e Patch faz uma alteração parcial da irformação. 
    -Patch -Quando você acessa uma rede social e altera seus atatus, está alteração de acontecer utilizando o método PATCH para envio da informção ao servidor. 
    -Put   -Utilizado para atualizar todos os dados de um cadastro


3) Assim como na aula, apresente os dados dos JSONs no console 
    - No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
    - No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console
    - No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.

4) Defina o conceito de idempotência e como uma API pode ser idempotente
    
    Métodos HTTP pode possuir a características idempotente ou não idempotente.
    
    2-idempotent. Se o método for idempotente, irá gerar mesmo o resultado dos conjuntos de recursos toda vez que for chamada. 
    Métodos idempotentes: GET,PUT,DELETE.
    Exemplo: GET acessa um cadastro. Sempre entregará o mesmo resultado. 
   
     O Post quando chamado, o servidor entende que hávera uma novo registro.
     Este método pode alterar um recurso ou afetar o banco de dados. 
     Exemplo: Quando o você cria uma conta em uma APP ou quando posta uma nova mensagem em uma rede social. 
    

5) Cite alguns diferentes padrões de projetos de software
    - Padrões criacionais 
        - O Singleton é um padrão de projeto criacional que permite a você garantir que uma classe tenha apenas uma instância, enquanto provê um ponto de acesso global para essa instância.

    - Padrões estruturais
        -O Proxy é um padrão de projeto estrutural que permite que você forneça um substituto ou um espaço reservado para outro objeto. Um proxy controla o acesso ao objeto original, permitindo que você faça algo ou antes ou depois do pedido chegar ao objeto original.
        
    - Padrões comportamentais  
        - O Observer é um padrão de projeto comportamental que permite que você defina um mecanismo de assinatura para notificar múltiplos objetos sobre quaisquer eventos que aconteçam com o objeto que eles estão observando.