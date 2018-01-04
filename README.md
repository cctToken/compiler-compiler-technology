## Software Developers -DApp- Community, using Compiler Compiler Technology  

# Table of Contents
* [CCT Information](#cct-information)
   - [Compiler Compiler System (CCS)](#compiler-compiler-system)
   - [Figure of a Traditional Compiler Compiler](#figure-of-a-traditional-compiler-compiler)
   - [Figure of our Compiler Compiler System](#figure-of-our-compiler-compiler-system)
   - [Compiler Compiler System Elements and Rules](#compiler-compiler-system-elements-and-rules)
   - [Compiler Compiler Technology Terms](#compiler-compiler-technology-terms)
   - [Installation](#installation)
   - [Download](#download)
   - [License](#license)
   - [Patent](#patent)
 * [CCT Integration with Community](#cct-integration-with-community)
    - [Purpose](#purpose)
 * [Comparison Analysis](#comparison-analysis)
   - [Artificial Intelligence](#artificial-intelligence)
   - [Internet of Things](#internet-of-things)
   - [Platform Platform](#platform-platform)
   - [Blockchain](#blockchain)
   - [Interoperability](#interoperability)
   - [Standardization](#standardization)
   - [Scalability](#scalability)
   - [Security based on Obfuscation](#security-based-on-obfuscation)
   - [Business Model](#business-model)

# CCT Information  

## Compiler Compiler System
[(Back to top)](#table-of-contents)  

*a compiler creating compilers.*  
The CCS is a tool, enabling programs to compile any source code. 
  
The CCS has a specific Source Grammar Definition Language, which is  
used as an input to generate a target parser with additional code,  
compiled and linked into an executable program.     
  
After the Compiler Compiler System runs, it creates a program   
that is ready to compile source code and also it is  
ready to generate syntax controlled binary, as well as it is  
ready to decompile binary to its original definition.     
  
The Compiler Compiler System's important feature of generating  
syntax controlled binary and then decompling that binary to its   
original form will prove to provide solutions to many technological  
slowdowns; Compilation, Interoperability, Obfuscation, Security,  
Content Management, Scaleability, Standardization.   
These areas, as well as their solutions, will be discussed further down.  
  
The Compiler Compiler System is a **tool**.  
  
Being a tool, it is about bettering the lives for software developers.  
  
## Figure of a Traditional Compiler Compiler
[(Back to top)](#table-of-contents)  
![alt text](http://compilercompilertechnology.com/wp-content/uploads/2017/12/Capture.png)



## Figure of our Compiler Compiler System
[(Back to top)](#table-of-contents)  
![alt text](http://compilercompilertechnology.com/wp-content/uploads/2017/12/Capture2.png)

The last stage in the diagram, **Stage 205**, results in  
a Compiler Compiler System executable program. This stage is generated from **Stage 201**,  
when inputed Compiler Compiler Source Grammar Definition Language text, which defines itself   
(regarded as meta grammar). Stage 201 performs **Phase 2.1a**, generating **Stage 202**,  
the Compiler Compiler Runtime API. The Compiler Compiler executable program from Stage 205,  
has an option to de-compile the, meta grammar generated, Compiler Compiler Runtime API into  
a text file (not shown), which contains the meta grammar executing phase, shown in Phase **2.1b**.      
This newly de-compiled meta grammar as a text, is identical to the meta grammar from  
Stage 201 except for some differences related to supported indentation rules.    
  
The Compiler Compiler executable program for the given meta grammar performs **Phase 2.2a**,  
generating the Compiler Compiler Binary API, **Stage 203** for the corresponding  
Compiler Compiler Runtime API. Phase 2.2a is implemented as a formal procedure that converts  
Compiler Compiler Runtime into Compiler Compiler Binary. The Compiler Compiler executable program    
has an option to de-compile the meta grammar, generated from the Compiler Compiler Binary, into a   
text file (not shown) containing the meta grammar executing phase, **Phase 2.2c**. This newly  
de-compiled meta grammar, as a text, is identical to meta grammar from Stage 201 except for some  
differences related to supported indentation rules.  
  
Having the Compiler Compiler Binary executing phase 2.2b, the Compiler Compiler  
executable program has an option to re-create a Compiler Compiler Runtime that  
is identical to the original Compiler Compiler Runtime from Stage 202. The Compiler Compiler  
executable program performs **Phase 2.3** creating  a Compiler compiler generated code,  
**Stage 204** corresponding to the meta grammar from Stage 201.   
  
## Compiler Compiler Technology Terms  
[(Back to top)](#table-of-contents)  
Source Grammar Definition Language  
Compiler Compiler Runtime API  
Compiler Compiler Binary API  
Compiler Compiler executable program  
  
## Meta Grammar Example:  
## As an example,  
When C++ compiler compiler executable program 205 takes the following meta grammar source file:    
(meta  
   (grammar ::=  
      0 =" METAACTBEG();"=  
      '(' grammarNameDef  
          { rule }  
       ')'  
        0 =" METAACTEND();"=    
 )  
 (grammarNameDef ::= identifier  
 )  
 (rule ::= '(' nterm '::=' right ')'  
 )  
 (nterm ::= identifier  
 )  
 (right ::= { element }  
 )  
 (element ::= identAlt | alternative | identMiss | iteration | action  
 )  
 (action ::= integerToken '=' { stringToken } '='  
 )  
 (actions ::= '=' { action } '='  
 )  
 (identAlt ::= ntermtermact { Altpart }  
 )  
 (Altpart ::= '|' ntermtermact  
 )  
 (ntermtermact ::= ntermterm [ actions ]  
 )  
 (ntermterm ::= nterm | termToken  
 )  
 (alternative ::= '(' identAlt ')'  
 )  
 (identMiss ::= '[' identAlt ']'  
 )  
 (iteration ::= '{' iterItemact iterItems '}'  
 )  
 (iterItems ::= { altIterItem }  
 )  
 (altIterItem ::= '|' iterItemact  
 )  
 (iterItemact ::= iterItem [ actions ]  
 )  
 (iterItem ::= nterm | maybeNterm  
 )  
 (maybeNterm ::= '<' nterm '>'  
 )  
)  
  
  
As a result of phase 2.3 the following C++ source files are generated:  
- metaGenerator.h  
- metaKeyWordDefinition.h  
- metaParser.h  
- metaGenerator.cc  
- metaKeyWordDefinition.cc  
- metaParser.cc  
- metaMakeGenerators.cc  
  
Note, that the 'meta' prefix in file names corresponds to the grammar name  
- the first section identifier in source grammar definition language.    
Note also that  
**0 =" METAACTBEG();"=**  
**0 =" METAACTEND();"=**  
are used as a special macro substitution actions defined in form of integer  
number followed by sequence of string  literals enclosed in '=' and '='.       
  
## Compiler Compiler System elements and rules      
[(Back to top)](#table-of-contents)  
The compiler compiler source grammar definition language elements such as '(' and ')'  
are grammar terminals defined as a string literal with enclosed single quotes.  
  
The Compiler Compiler Source Grammar Definition Language consists of a grammar "name"  
section followed by a sequence of rules where the first rule is also a grammar axiom.  
As used  herein, the grammar name section consists of a single identifier that defines a name of grammar.  
  
**The compiler compiler source grammar definition language element:**    
{ rule }  
*is a BNF extension called iteration, meaning that enclosed by { and } 
non-terminal may occur zero or any  other number of times.*  
Note, that, e.g., rule  
         (iterationExample ::= { element } )  
         is equivalent to rules  
         (iterationExample ::= element iterationExample )  
         (iterationExample ::= )  
  
**The compiler compiler source grammar definition language rule:**    
 (rule ::= '(' nterm '::=' right ')'  
 )  
*defines rule as a terminal '('  
followed by non-terminal nterm, followed by terminal '::=',  
followed by non-terminal right, followed by terminal ')'.*  
  
**The compiler compiler source grammar definition language rule:**  
 (nterm ::= identifier  
 )  
*defines non-terminal nterm as identifier.*  
  
**The compiler compiler source grammar definition language rule:**    
 (right ::= { element }  
 )  
*defines non-terminal right as an iteration of element non-terminals.*  
  
**The compiler compiler source grammar definition language rule:**    
 (element ::= identAlt | alternative | identMiss | iteration | action    
 )    
*defines non-terminal element as an alternative of non-terminals on the right side of  
rule definition separated by '|'. The alternative is BNF extension similar to  
iteration extension; it is used in cases when non-terminal on the left side of  
rule definition can be one of non-terminals from the right side.*  
Note, that, e.g., rule  
      (alternativeExample ::= A | B | C | Z )  
      is equivalent to rules  
      (alternativeExample ::= A )  
      (alternativeExample ::= B )  
      (alternativeExample ::= C )  
      (alternativeExample ::= Z )
  
**The compiler compiler source grammar definition language rule:**    
 (action ::= integerToken '=' { stringToken } '='  
 )  
*defines non-terminal action as an integerToken followed by terminal '=',  
followed by iteration of stringToken followed by terminal '='. Here integerToken   
and stringToken are another Compiler Compiler Source Grammar Definition Language  
reserved key words similar to identifier. integerToken defines token that holds  
integer value. stringToken defines token that holds string literal value as an  
arbitrary sequence of any characters enclosed with double quotes, i.e., ".*  
  
**The compiler compiler source grammar definition language rule:**    
 (actions ::= '=' { action } '='  
 )  
*defines non-terminal actions as a iteration of action enclosed with '='.*    
  
**The compiler compiler source grammar definition language rule:**    
 (identAlt ::= ntermtermact { Altpart }  
 )  
*defines non-terminal identAlt as a ntermtermact followed by iteration of Altpart non-terminals.*  
  
**The compiler compiler source grammar definition language rule:**    
 (Altpart ::= '|' ntermtermact  
 )  
*defines non-terminal Altpart as a terminal '|' followed by non-terminal ntermtermact.*  
  
**The compiler compiler source grammar definition language rule:**    
 (ntermtermact ::= ntermterm [ actions ]  
 )  
*defines non-terminal ntermtermact as a non-terminal ntermterm followed by [ actions ] meaning that  
non-terminal actions may be omitted. Non-terminal enclosed with [ and ] is another compiler compiler  
source grammar definition language BNF extension representing elements that can be omitted.*  
Note, that, e.g., rule  
      (ommitedElementExample ::= A [ W ])  
      is equivalent to rules:  
      (ommitedElementExample ::= A Welement )    
      (Welement::= W )  
      (Welement::= )  
  
**The compiler compiler source grammar definition language rule:**    
 (ntermterm ::= nterm | termToken  
 )  
*defines non-terminal ntermterm as an alternative of nterm of termToken. nterm is defined above.  
termToken is another compiler compiler source grammar definition language reserved key word that defines    
terminal token specification as a string literal enclosed with single quotes.*  
  
**The compiler compiler source grammar definition language rule:**    
 (alternative ::= '(' identAlt ')'  
 )  
*defines non-terminal alternative as an identAlt enclosed with terminals '(' and ')'.*  
  
**The compiler compiler source grammar definition language rule:**    
 (identMiss ::= '[' identAlt ']'  
 )  
*defines non-terminal identMiss as an identAlt enclosed with terminals '[' and ']'.*   
  
**The compiler compiler source grammar definition language rule:**      
 (iteration ::= '{' iterItemact iterItems '}'  
 )   
*defines non-terminal iteration as an iterItemact followed by non-terminal iterItems enclosed with  
terminals '{' and '}'.*  
  
**The compiler compiler source grammar definition language rule:**      
 (iterItems ::= { altIterItem }  
 )  
*defines non-terminal iterItems as an iteration of altIterItem non-terminals.*    
  
**The compiler compiler source grammar definition language rule:**     
 (altIterItem ::= '|' iterItemact  
 )  
*defines non-terminal altIterItem as terminal '|' followed by non-terminal iterItemact.*  
  
**The compiler compiler source grammar definition language rule:**      
 (iterItemact ::= iterItem [ actions ]  
 )  
*defines non-terminal iterItemact as non-terminal iterItem followed by [ actions ].*   
  
**The compiler compiler source grammar definition language rule:**    
 (iterItem ::= nterm | maybeNterm  
 )  
*defines non-terminal iterItem as an alternative of non-terminals nterm and maybeNterm.*    
  
**The compiler compiler source grammar definition language rule:**    
 (maybeNterm ::= '<' nterm '>'  
 )  
*defines non-terminal maybeNterm as non-terminal nterm enclosed between terminals '<' and '>'.*  
  
The compiler compiler source grammar definition language iteration is actually defined as  
a sequence of terminals or nonterminals may be followed by actions, and also non-terminals  
may be enclosed between terminals '<' and '>' meaning that such non-terminal is allowed to  
be in iteration only zero or one time.     
Note, that, e.g., the rule  
      (anotherIterationExampe :: = { A | B | <X> | <Z> } )  
      is equivalent to the rules  
      (anotherIterationExampe :: = elem anotherIterationExampe )  
      (anotherIterationExampe :: = )  
      (elem ::= A | B | X | Z )  
  
## Download  
//zip (after edit)

## Installation  
//clean up installment-> Download Instructions  
Download Video  
  
## License    
[License](http://compilercompilertechnology.com/wp-content/uploads/2018/01/CCTDevelopmentAndInternalUseLicenseFinal.pdf)
  
   
## Patent  
[Patent](http://compilercompilertechnology.com/wp-content/uploads/2017/03/US-08464232.pdf)  
 
---   
[(Back to top)](#table-of-contents)  
---  
  
  
# CCT Integration with Community  
  
## Purpose
[(Back to top)](#table-of-contents)
   
  
# Comparison Analysis
[(Back to top)](#table-of-contents)
  
## Artificial Intelligence
[(Back to top)](#table-of-contents)
  
## Internet of Things
[(Back to top)](#table-of-contents)
  
## Platform Platform
[(Back to top)](#table-of-contents)
  
## Blockchain
[(Back to top)](#table-of-contents)
  
## Interoperability
[(Back to top)](#table-of-contents)
  
## Standardization
[(Back to top)](#table-of-contents)
  
## Scalability
[(Back to top)](#table-of-contents)
  
## Security Based On Obfuscation
[(Back to top)](#table-of-contents)
  
## Business Model
[(Back to top)](#table-of-contents)
  



