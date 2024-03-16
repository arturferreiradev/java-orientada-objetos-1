# Programação Orientada a Objetos Java

A Programação Orientada a Objetos (POO) é um paradigma de programação que organiza o código em torno de objetos, que representam entidades do mundo real e possuem características (atributos) e comportamentos (métodos). Dentre os paradigmas mais populares e amplamente utilizados na indústria de desenvolvimento de software, a POO se destaca por permitir a criação de sistemas mais flexíveis, modulares, reutilizáveis e fáceis de manter.

## Classe

* É um tipo estruturado que pode conter (membros):
	* Atributos (dados / campos)
	* Métodos (funções / operações)

* A classe também pode prover muitos outros recursos, tais como:
	* Construtores
	* Sobrecarga
	* Encapsulamento
	* Herança
	* Polimorfismo

* Exemplos:
	* Entidades: Produto, Cliente, Triangulo
    * Serviços: ProdutoService, ClienteService, EmailService, StorageService
    * Controladores: ProdutoController, ClienteController
    * Utilitários: Calculadora, Compactador
    * Outros (views, repositórios, gerenciadores, etc.)

* Classe é a definição do tipo

## Objeto

* São instâncias de classes, que possuem atributos e comportamentos.

* Instanciação: alocação dinâmica de memória

## Métodos

* Os métodos determinam o comportamento dos objetos de uma classe e são análogos a funções ou procedimentos da programação estruturada. 

* Permite a reutilização de código: criação de sistemas mais eficientes, pois as classes derivadas podem herdar características e comportamentos de classes base.

## Construtor

* É uma operação especial da classe, que executa no momento da instanciação do objeto

* Usos comuns:
    * Iniciar valores dos atributos
    * Permitir ou obrigar que o objeto receba dados / dependências no momento de sua instanciação (injeção de dependência)

* Se um construtor customizado não for especificado, a classe disponibiliza o construtor padrão:  
`Product p = new Product();`

* É possível especificar mais de um construtor na mesma classe (sobrecarga)

## Palavra this

* É uma referência para o próprio objeto

* Usos comuns:
    * Diferenciar atributos de variáveis locais
    * Passar o próprio objeto como argumento na chamada de um método ou construtor

## Sobrecarga

* É um recurso que uma classe possui de oferecer mais de uma operação com o mesmo nome, porém com diferentes listas de parâmetros.

## Encapsulamento

* É um princípio que consiste em esconder detalhes de implementação de uma classe, expondo apenas operações seguras e que mantenham os objetos em um estado consistente.

* Regra de ouro: o objeto deve sempre estar em um estado consistente, e a própria classe deve garantir isso.

* Regra geral básica
    * Um objeto NÃO deve expor nenhum atributo (modificador de acesso private)
    * Os atributos devem ser acessados por meio de métodos get e set

## Gerando automaticamente construtores, getters e setters com Eclipse

Comandos:

* Botão direito -> Source -> Generate Constructor using Fields
* Botão direito -> Source -> Generate Getters and Setters

## Modificadores de acesso

* private: o membro só pode ser acessado na própria classe

* (nada): o membro só pode ser acessado nas classes do mesmo pacote

* protected: o membro só pode ser acessado no mesmo pacote, bem como em subclasses de pacotes diferentes

* public: o membro é acessado por todas classes (ao menos que ele resida em um módulo diferente que não exporte o pacote onde ele está)









