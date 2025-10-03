Aqui estão as respostas diretas:

1. Em Java o código é compilado para bytecode (independente de plataforma) e executado pela JVM; em C++ é compilado diretamente para código de máquina específico do sistema operacional e hardware.

2. Análise Léxica: converte o código-fonte em tokens (palavras-chave, identificadores, símbolos).

Análise Sintática: verifica se a sequência de tokens obedece à gramática da linguagem (estrutura correta).

Análise Semântica: checa significados (tipos, variáveis declaradas, coerência do código).


3. O bytecode é o código intermediário gerado pelo compilador; sua função é permitir que o programa seja executado em qualquer sistema com JVM.

4. A JVM interpreta ou compila o bytecode para instruções nativas do sistema. O arquivo .class não roda diretamente porque não contém código de máquina específico, mas sim instruções portáveis.

5. O JIT (Just-In-Time Compiler) compila partes do bytecode em código nativo durante a execução, melhorando o desempenho.

6. A aplicação mais comum das linguagens formais em Java é na definição de gramáticas para análise léxica e sintática, usadas na construção de compiladores e interpretadores.

7. Na Análise Léxica, usam-se expressões regulares para reconhecer tokens.

Na Análise Sintática, usam-se gramáticas formais para validar a estrutura do programa.


8. Uma FSM (Máquina de Estados Finitos) é um modelo matemático de computação baseado em estados e transições; em Java pode ser usada em parsers, jogos, protocolos de rede e validação de entradas.

9. Linguagens formais servem como base para definir regras de validação em schemas de XML e JSON, garantindo que os documentos sigam uma estrutura bem definida.

10. O ANTLR é usado para gerar analisadores léxicos e sintáticos a partir de gramáticas, facilitando a criação de compiladores e interpretadores em Java.

