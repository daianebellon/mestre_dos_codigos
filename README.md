# Mestre Dos Códigos
1 - O Básico de Java:

O Java foi criado em 1991, na Sun Microsystems, com intuito que os aparelhos eletrônicos se comunicassem entre si. Teve inicio com o Green Project, no qual os mentores foram Patrick Naughton, Mike Sheridan, e James Gosling.
Java é uma linguagem relativamente simples e dinâmica, permite criar programas e aplicações para a Web sem depender de outra linguagem.
É uma das plataformas de desenvolvimentos mais utilizadas e aceitas no mercado. Isso se deve a algumas características como a portabilidade e simplicidade.
O Java é uma linguagem Orientada a Objetos, possui alta performance, é tipada e independente da plataforma.
Ela foi a primeira a utilizar decodificadores de televisões interagindo em dispositivos portáteis e outros produtos eletrônicos de consumo.
Uma curiosidade sobre o nome da linguagem ser “Java” é que no início, antes de definir Java, pensaram em “ Oak”, porém esse nome já estava em uso. O nome Java surgiu em uma cafeteria, ao qual o grupo criador do projeto sempre tomava café. “Java”, pois era o nome da terra de origem do café, que os programadores da equipe apreciavam nessa cafeteria, por isso que a logo do Java é um café.
Em 2003 o Java já tinha mais de 4 milhões de desenvolvedores.

A JVM é um computador virtual que entende apenas um código específico chammado de ByteCode, que é gerado pelo compilador Java(Javac). Esse código será traduzido pela Virtual Machina para o código da máquina em questão.

O JDK é um conjunto de utilitários que permitem a criação de jogos e programas para a plataforma Java. Ele é composto pelo compilador e pelas bibliotecas necessárias para a criação de programas em Java.

O JRE é o que possibilita que um programa Java seja executado em qualquer sistema operacional sem modificação, pois ele combina código Java criado usando o JDK com as bibliotecas necessárias para executá-lo em uma JVM e, em seguida, cria uma instância da JVM que executa o programa resultante.

Em Java, uma classe executável é uma classe que possui um método inicial para a execução do programa - o método main, que será chamado pela JVM. Classes sem o método main não são classes executáveis e não podem ser usadas como ponto incial da aplicação. O método main deve ser público, estático, não ter retorno, ter o nome main e receber como parâmetro um array ou vargargs de String.
Para executar uma classe com main por exemplo:

```
public class HelloWorld {
  
    public static void main(String[] args) {
        System.out.println("Hello World!);
    }
}
```
Para rodar o código Java, é necessário compilá-lo para bytecodes, pois é o código que a JVM entende.
Para compilar: <b>javac HelloWorld.java</b>

Para executar: <b>java HelloWorld</b>

O resultado será:
```
Hello World!
```
Durante muito tempo, uma das maiores dificuldades na hora de programar era o gerenciamento de memória. Os desenvolvedores eram responsáveis pela sua alocação e liberação manualmente, o que levava a muitos erros e memory leaks. Hoje, em todas as plataformas modernas (incluindo Java), temos gerenciamento de memória automático através de algoritmos de coleta de lixo. 
A técnica de Coleta de Lixo consiste na recuperação segura do espaço de memória ocupado por um objeto que não é mais referenciado dentro de uma aplicação.
Com o uso do Garbage Collector o problema de referências pendentes, isto é, quando o programador desaloca o espaço ocupado por um objeto que ainda está sendo referenciado, nunca acontece, pois um objeto que ainda está sendo referenciado jamais será candidato – ou elegível – à coleta de lixo e seu espaço de memória não ficará livre.
Esta maneira de gerenciar o espaço também resolve o problema do vazamento de memória, visto que toda memória não mais referenciada é liberada automaticamente.

Um Garbage Collector tem a função de:
- Alocar memória;
- Assegurar que quaisquer objetos referenciados permaneçam na memória;
- Recuperar a memória alocada pelos objetos que não são mais alcançáveis pelas referências no código em execução.

A ausência de um gerenciamento adequado de memória pode causar uma exceção do tipo OutOfMemoryException. Esse é um dos principais motivos pelos quais o programador precisa conhecer o funcionamento do Coletor de Lixo, pois mesmo que o desenvolvedor não precise se preocupar em liberar explicitamente a memória ocupada pelos objetos candidatos à coleta, ele ainda necessita tratar de tornar elegíveis os objetos que não forem mais úteis à aplicação.



