<!-- 
    String

    "" // aspas duplas;
    '' // aspas simples;
    `` // template literals ou template strings;
    ${} // interpolação;

    Números

    33 // inteiros;
    12.5 // reais - float;
    NaN // Not a Number;
    Infinity // infinito;

    Boolean
        * somente 2 valores;

    true // verdadeiro;
    false // falso;

    Undefined
        * indefinido;

    Null
        * nulo;
        * objeto que não possui nada dentro;
        * diferente de indefinido;

    Object
        * Objeto;
        * Propriedades // Atributos;
        * Funcionalidades // Métodos;
        { propriedades: "valor" }

    Array (vetores)
        * Uma lisa;
        * Agrupamento de dados;

    Data types
        * Primitive // Primitive value;
        * Structural;
        * Structural Primitive;

        ## Primitivos
            * String;
            * Number;
            * Boolean;
            * undefined;
            * Symbol;
            * BigInt;

        ## Estruturais
            * Object;
                * Array;
                * Map;
                * Set;
                * Date;
                * ...
            * Function;

        ## Primitivo Estrutural // Structural Root Primitive
            * null;

    Variáveis
        * var;
        * let;
        * const;

    Scope
        * Escopo determina a visibilidade de alguma variável;
        * Obloco, também criará um novo escopo. Chamamos de `block-scoped`;
        * Const e let são locais e só funcionam no escopo onde foram criadas;
        * Escopo são "grupos de pessoas conversando", o "Marcos" de um grupinho, não é o mesmo de outro grupinho;

    Var Names
        * Case-sensitive;
        * Iniciar com letras, acentos é permitido;
        * Letras maiusculas e minusculas fazem diferença;
        * Criar nomes que fazem sentido e que explique o que a variável é ou faz;
        * camelCase;
        * snake_case;
        * Escrever em inglês;

    Tips
        * Usou duas "!!", converteu para o tipo bool;
        * Usou uma "!", converteu para o inverso do valor, ou seja, se era "true" virou "false", se era "false", virou "true";
        * Em listas, a primeira posição possui o índice 0;
        * Podemos fazer agrupamento de declarações "let name, age" e posteriormente declararmos "name = Rafael", "age = 18";
        * Podemos concatenar valores através do "+";
        
    Function
        * O papel da função é agrupar um código e tornar possível sua reutilização;
        * Ao invés de ficarmos repetindo um pedaço de código, criamos uma função;
        * Toda função pode ou não, receber parâmetros, argumentos;
        * Podemos declarar funções dentro de variáveis;
        * Function anonymous;
        * Quando uma função não tem o termo "return", ela retorna o valor "undefined"

            Explicando melhor
                * Uma função é um liquidificador
                    function fazerSuco(fruta1, fruta2){
                        return fruta1 + fruta2
                    }

                    const copo = fazerSuco("banana", "maçã")
                    console.log(copo)
        
        * Function scope;
        * Function hoisting;
        * Arrow function;
        * Callback function;
            * É uma função que está sendo passada como parâmetro dentro de outra função;

            function brincarComAmigo(callback) {
                console.log("Esperando o amigo...");
                callback();  // Isso chama de volta o amigo para brincar!
            }

            function amigoChegou() {
                console.log("Amigo chegou! Vamos brincar juntos!");
            }

            brincarComAmigo(amigoChegou);

        * Function constructor;
            * Expressão "new";
            * Criar um novo objeto;
            * "this" keyword;

    Prototype
        * prototype-based language;
        * prototype chain;
        * __proto__;
        * Dominar isso aqui, irá ajudar muito a dominar a manipulação de dados;

    Expressões e operadores
        * Expressions;
            let number = 1;

        * Operators;
            * Binary;
                number + 1

            * Unary;
                ++number

            * Ternary;
                true ? 'alo' : 'nada'
            
    new
        * left-hand-side expression;
        * cria um novo objeto;

    Operadores unários
        * typeof;
        * delete;
    
    Operadores Aritiméticos
        * multiplicação;
            console.log(3.2 * 5)

        * divisão;
            console.log(12 / 2)

        * soma;
            console.log(34 + 42)

        * subtração;
            console.log(32 - 7)

        * resto da divisão;
            console.log(11 % 3)

        * incremento;
            let increment = 1
            increment++
            console.log(increment)

        * decremento;
            let decrement = 1
            console.log(--decrement)

        * exponencial;
            console.log(3 ** 3)
        
    Grouping Operator
        * ()
    
    Operadores de comparação
        * =
        * ==
        * !=
        * estritamente igual a;
            * ===
        * estritamente diferente de;
            * !==
        * maior que;
            * >
        * maior igual a;
            * >=
        * menor que;
            * <
        * menor igual a;
            * <=
    
    Operadores de atribuição
        * assigment;
            * x = 1;
        
        * addiction assigment;
            * x += 2;
        
        * subtraction assigment;
            * x -= 1;

        * multiplication assigment;
            * x *= 2;
        
        * division assigment;
            * x /= 3;

        * remainder assigment;
            * x %= 2;
        
        exponetiation assigment;
            * x **= 2;

    Operadores lógicos (logical operators)
    
 -->