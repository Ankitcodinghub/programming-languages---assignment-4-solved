# programming-languages---assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [Programming Languages – Assignment 4 Solved](https://www.ankitcodinghub.com/product/programming-languages-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113759&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Languages - Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
The goal of this assignment is to create a C program which:

-takes a text file as input

-tokenizes the given input

-Parses the tokenized input to determine if it is grammatically valid

This program will consist of four class files: Givens.c Tokenizer.c Parser.c and Analyzer.c . Each class file has a corresponding header file where all constants, method declarations, struct definitions, include statements, and global variables will be placed. (Header files are named the same as their corresponding class file but with a .h file extension rather than a .c file extension) Tokenizer.h and Parser.h will include Givens.h and Analyzer.h will include both Tokenizer.h and Parser.h .

Givens.c

Givens.c is provided with this assignment. Givens.c includes constants for TRUE and FALSE, constants for all token values in the given lexical structure, a constant for the max size of a lexeme, and the definition for a struct named lexics, which consists an int property named token and a character array property named lexeme. The lexics struct is used to store both a token and its corresponding lexeme. Givens.c also provides two functions which return a boolean value indicating if the given String matches a specified regular expression.

Tokenizer.c

Tokenizer.c is not provided and needs to be created. Tokenizer.c will read characters from a given FILE variable and convert them into tokens. It will do so using a function defined as follows:

_Bool tokenizer(struct lexics *aLex, int *numLex, FILE *inf);

Which takes an array of type lexics, an int pointer representing the number of tokens in the input file, and a pointer to a FILE. The tokenizer function will read characters from the given FILE parameter, creating lexemes and the associated tokens. Each time a lexeme is generated, a new lexics struct will be created and the lexeme added. The generated lexeme is then tokenized, the token is added to the generated lexics struct, the lexics struct is then added to the end of the given lexics array. (Note: another option is to generate lexemes first, then tokenize the generated lexemes)

The given lexical structure is free format and the location of tokens in the text file does not affect their meaning. Alphanumeric lexemes will be delimited by both whitespace and by character lexemes. Because character lexemes are used as delimiters, they cannot be constructed one token at a time. Rather the next several tokens in the file will need to be examined to determine which (if any) character lexeme is present.

The use of helper functions in the Tokenizer.c class is highly recommended. Once the tokenization process is complete, the tokenizer function should return TRUE. If there occurs an error in the process, the function should return FALSE.

Parser.c

Parser.c is not provided and needs to be created. Parser.c will implement a recursive decent parser based upon a provided EBNF grammar. It will do so using a function defined as follows:

_Bool parser(struct lexics *someLexics, int numberOfLexics);

Which takes an array of type lexics and an int pointer representing the number of tokens in the given lexics array. The parser method must take the given array of lexics structs and determine if it is legal in the language defined by the given grammar. The purpose of our parser is to apply the grammar rules and report any syntax errors. If no syntax errors are identified, parser returns TRUE, otherwise it returns FALSE.

Parser.c must be a recursive decent predictive parser which utilizes single-symbol lookahead. Parsers which utilize multi-symbol lookahead will not be accepted. If given a grammatically valid input, every token given must be parsed. If a syntax error is found, parsing does not need to continue. Parsers which do not consume every given token for a grammatically valid input will not be accepted.

Analyzer.c

Analyzer.c is provided with this assignment. Analyzer.c includes a method to prompt the user for a file path, the initialization of an array of type lexics and an int containing the number of lexics in the array (initialized to 0). Analyzer.c makes calls both the tokenizer method and the parser method, passing the initialized int an array to both functions.

Provided EBNF grammar:

function –&gt; header body

header –&gt; VARTYPE IDENTIFIER LEFT_PARENTHESIS [arg-decl] RIGHT_PARENTHESIS

arg-decl –&gt; VARTYPE IDENTIFIER {COMMA VARTYPE IDENTIFIER}

body –&gt; LEFT_BRACKET [statement-list] RIGHT_BRACKET

statement-list –&gt; statement {statement}

statement –&gt; while-loop | return | assignment | body

while-loop –&gt; WHILE_KEYWORD LEFT_PARENTHESIS expression RIGHT_PARENTHESIS statement

return –&gt; RETURN_KEYWORD expression EOL

assignment –&gt; IDENTIFIER EQUAL expression EOL

expression –&gt; term {BINOP term} | LEFT_PARENTHESIS expression RIGHT_PARENTHESIS

term –&gt; IDENTIFIER | NUMBER

Provided lexical structure:

LEFT_PARENTHESIS –&gt; (

RIGHT_PARENTHESIS –&gt; )

LEFT_BRACKET –&gt; {

RIGHT_BRACKET –&gt; }

WHILE_KEYWORD –&gt; while

RETURN_KEYWORD –&gt; return

EQUAL –&gt; =

COMMA –&gt; ,

EOL –&gt; ;

VARTYPE –&gt; int | void

IDENTIFIER –&gt; [a-zA-Z][a-zA-Z0-9]*

BINOP –&gt; + | * | != | == | %

NUMBER –&gt; [0-9][0-9]*

Grading Rubric:

Category Points

Functions and Classes properly defined 10

Header files correctly utilized 10

Tokenizer.c produces correct output 32.5

Parser.c produces correct output 32.5

Code is well commented 7.5

Code is well formatted 7.5

Total 100
