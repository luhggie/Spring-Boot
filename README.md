# Spring-Boot

- Spring Framework: é um framework que facilita a aplicação do java em sistemas web conseguindo criar aplicações entrando no modo just run
- Spring Boot: uma camada superficial que facilita a utilização do framework


Classe princiapl: nomeDoProjetoApplication
- Classe de entrada que chama a execução de toda a aplicação

Classe Controller: uma classe que vai receber requisições HTTP 
- Criamos um endpoint:

Classe Service: contém a lógica das regras do controller 

*Anotações*: começam com @ e servem para fazer configurações da nossa classe 
- @SpringBootApplication: define a porta de entrada do SpringBoot. Ativa auto configuração so pring
- @RestController: indica de essa classe é um controler REST (não mantém o estado do cliente) e retorna uma resposta HTTP
- @RequestMapping(NomeDoParametroQueQUerMapear): mapeia uma requisição
- @GetMapping: endpoint responde a uma requisicão do método GET do HTTP
- @PostMapping(), @PutMapping(), @DeleteMapping() e @PatchMapping(): mesma coisa que o GET porém para os outros métodos de HTTP
- @RequestParam: ega valores que vêm na query string (depois de ?) — usados para filtros, paginação, ordenação, flags etc.
- @PathVariable: pega valores que fazem parte do caminho (path) da URL — normalmente identificadores de recurso.

*Dicionário*

**Framwork**: É um conjunto de ferramentas + regras + estruturas prontas para você construir software mais rápido e de forma padronizada.
é uma estrutura COMPLETA de desenvolvimento que dita como sua aplicação deve ser construída, fornecendo diretrizes já prontas
A ideia central é inversão de controle (IoC): em vez de você chamar o framework, ele chama o seu código nos lugares certos do ciclo de vida.
A função é simplificar o desenvolvimento de aplicação impedidndo que o desenvolvedor tenha que começar tudo do zero

**API**: Um conjunto de definiç~ies e protocolos que permite que diferentes softwares interajam entre si
A função é permitir que uma aplicação utilize funcionalidades de outra sem precisar conhecer a implementação interna dela

**EndPoint**: Um endpoint é um “ponto de entrada” de um serviço: endereço + método onde seu app recebe uma requisição e responde algo.

**JSON**: JSON é um formato de dados (texto) para trocar informação entre sistemas. O nome vem de JavaScript Object Notation
