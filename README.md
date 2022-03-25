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

Em Java, uma classe executável é uma classe que possui um método inicial para a execução do programa - o método main, que será chamado pela JVM. Classes sem o método main não são classes executáveis e não podem ser usadas como ponto incial da aplicação. O método main deve ser público, estáticvo, não ter retorno, ter o nome main e receber como parâmetro um array ou vargargs de String.
Para executar uma classe com main por exemplo:

```
public class HelloWorld {
  
    public static void main(String[] args) {
        System.out.println("Hello World!);
    }
}
```
Para compilar: <b>javac HelloWorld.java</b>

Para executar: <b>java HelloWorld</b>

O resultado será:
```
Hello World!
```

