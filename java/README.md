![___image___)](https://user-images.githubusercontent.com/60306241/77236909-bf343d80-6ba1-11ea-828f-5cfd5011c557.png)

# Aprenda Java
>  :java: Aprenda o básico de Java

# Tópicos
- [Baixe o JDK do Java que é necessaria para desenvolver em Java](https://www.oracle.com/technetwork/pt/java/javase/downloads/index.html)
- [Apresentação](#apresentação) 
- [Escolhendo sua IDE ou Editor de texto](#escolhendo-sua-ide-ou-editor-de-texto)
- [Alguns entendimentos básicos](#entendimentos-básicos)
- [Estruta do Código](#estrutura-do-código)
- [Hello World](#hello-world)

## Apresentação
###### Olá meu nome é Carlos Alessandro,
###### costumo programar em js com o nodeJS, porém também amo java.
###### Para saber mais sobre mim olhe o meu [Github](https://github.com/magc7x)
&nbsp;
## Escolhendo Sua IDE ou Editor de texto
###### Caso você não saiba o que é uma IDE,  [Clique aqui](https://www.youtube.com/watch?v=GPcIjsz-2cA)
###### Como opções de IDE temos o [Eclipse](https://www.eclipse.org/), o [Netbeans](https://netbeans.org/) e o [IntelliJ](https://www.jetbrains.com/idea/)  é claro que existem outras mas essas são as mais famosas.
###### Como opção de Editor de texto eu recomendo o [Visual Studio Code](https://code.visualstudio.com/) .
&nbsp;
## Entendimentos Básicos
##### Compilador Java 
###### O compilador verifica seu código nas regras de sintaxe da linguagem e depois grava bytecode em arquivos .class. Bytecode é um conjunto de instruções destinadas a executar em uma Java virtual machine (JVM).  
&nbsp;
##### JVM
###### No tempo de execução, a JVM lê e interpreta arquivos .class e executa as instruções do programa na plataforma de hardware nativa para qual a JVM foi escrita.
&nbsp;
##### Garbage Collector
###### Em vez de forçá-lo a manter a alocação de memória (ou usar uma biblioteca de terceiros para isso), a plataforma Java fornece gerenciamento de memória fora do padrão. Quando seu aplicativo Java cria uma instância de objeto no tempo de execução, a JVM aloca automaticamente espaço de memória para esse objeto a partir de um conjunto de memória heap— reservado para uso de seu programa. O garbage collector do Java é executado em segundo plano, mantendo o controle de quais objetos o aplicativo não necessita mais e recuperando memória deles.
&nbsp;
# Básico
## Estrutura do Código
###### Considerando que você já se familiarizou com sua IDE ou Editor de texto vamos começar .
#### Entendendo Package , Class e Main
###### Após criar um projeto veremos a estrutura do nosso código inicial em Java.
###### (Caso esteja usando um editor de texto essa é a estrutura do código Java)
```java
package nomePackage;
public class nomeClasse {
  public static void main(String[] args) {
  
  }
}
```
#### Main
###### Acima podemos ver o seguinte trecho de código.
```java
public static void main(String[] args) {

}
```
######  O main é onde fica seu código , quando você compilar o seu programa o que vai ser executado é o que estiver dentro do escopo(tudo que está entre as chaves) do main.
###### Mais pra frente você vai entender melhor o que cada palavrinha dessa significa...
#### Classes
###### Acima podemos ver o seguinte trecho de código.
```java
public class nomeClasse {

}
```
###### O Java é uma linguagem orientada a objeto (você já deve ter ouvido falar sobre isso).
###### Caso não tenha ouvido, não se preocupe, mais para frente você verá isso mais a fundo.
###### Vamos pular isso por enquanto para não confundir sua cabeça.
###### 
#### Package
###### Acima podemos ver o seguinte trecho de código.
```java
package nomePackage;
```
###### A palavra package em inglês significa pacote. 
###### Dito isso o package é o lugar onde suas Classes irão ficar. 
###### Podemos pensar que o package funciona como uma pasta com varios arquivos .java dentro.

## Hello World
###### Para fazer um hello world no Terminal, podemos fazer de alguns jeitos vamos ver abaixo.
```java
package nomePackage;
public class nomeClasse {
  public static void main(String[] args) {
    //primeiro modo
    System.out.print("Hello World");
  
    //segundo modo
    System.out.println("Hello World");

    //terceiro modo
    System.out.printf(" Hello World ");
  }
}
```
###### Obs.: [Caso queira pular essa explicação não tem problema afinal você já sabe fazer um Hello World](#variáveis). 
###### Vamos falar de cada um...
###### Podemos ver  que todos tem algo em comum isso é as palavras "System" , "out" e "print".
```txt
A palavra "System" se refere a classe System 
que é uma classe padrão do java.
```
```txt
A palavra "out" se refere ao fluxo de saída padrão.
```
```txt
A palavra "print" traduzida pro português significa "impressão"
e é justamente isso que ela faz.
```
###### Mas o que realmente importa aqui  são os prints.
```java
System.out.print();
/*
esse print simplesmente vai mostrar na tela o que for colocado
entre os parênteses.
*/

System.out.println();
/*
esse print além de mostrar o que for colocado entre os 
parênteses ele automaticante vai pular uma linha no final 
do que estiver entre os parênteses.
*/

System.out.printf();
/*
não irei explicar a fundo exxe print agora , mas você ja sabe
que existe.
*/
```
######  https://docs.oracle.com/javase/7/docs/api/java/lang/System.html

## Variáveis
###### Coming Soon...