                                                                     L1: JAVA
                                                                     
                                                                     
HISTÓRICO E APRESENTAÇÃO

A linguagem de programação chamada de Oak (carvalho) foi criada pelo chefe do projeto James Gosling.
A história começa em 1991, em San Hill Road, empresa filiada a Sun (da qual hoje pertence a empresa Oracle), formado pelo time de engenheiros liderados por Patrick Naughton, Sun Fellow e James Gosling.
A ideia  da criação da linguagem era possibilitar a criação de programas portáveis que pudessem ser executados em diversos dispositivos, 
- Java é uma linguagem relativamente simples e dinâmica, permite criar programas e aplicações para a Web sem depender de outra linguagem.
- Segue o paradigma de orientação a objetos(Representa o mundo real)..
- Java é híbrida: o código é compilado para bytecode e o bytecode é interpretado pela máquina virtual Java (JVM).
- O JAVA é sensível à utilização de maiúsculos;
- Estilo de tipagem: estática · forte
-  JAVA é multiplataforma.
- API 's de segurança: As bibliotecas de classes Java fornecem várias APIs que levam à segurança. Essas APIs contêm algoritmos criptográficos e protocolos de autenticação que levam à comunicação segura.

Alguns das populares IDE´s utilizadas para o desenvolvimento de aplicações Java:
- IntelliJ IDEA 13.1, Eclipse, Netbeans, Oracle Jdeveloper.

Frameworks de suporte ao desenvolvimento: Cucumber-JVM, Docker, Maven, Spring tools.


Métodos: sobrecarga e parâmetros. Permite sobrecarga de métodos e permite declarar métodos com números variáveis de parâmetros. Exemplo de código de declaração, implementação e chamada de método com número variável de parâmetros::
public class Main {
        public static void metodo(int ... x) {
                for (int i : x) {
                        System.out.println(i);
                }
        }
        public static void main(String[] args) {
                metodo(1, 2, 3, 4);
        }
}

- não permite declarar valores default para os parâmetros;

- Visibilidade: Possui mecanismos para controlar o acesso (visibilidade) a métodos e atributos de uma classe.

- polimorfismo é a capacidade de um objeto ser referenciado de diversas formas diferentes e com isso realizar as mesmas tarefas (ou chamadas de métodos) de diferentes formas.

- Convenções usadas para nomear classes: upper camel case: apenas a primeira letra de cada palavra maiúscula; sem separador entre palavras.
- Convenções usadas para nomear métodos: lower camel case: inicia com letra minúscula; todas as palavras a partir da segunda iniciam com letra maiúscula; sem separador entre palavras;
- O gerenciamento de memória é via garbage collector(remove a responsabilidade do gerenciamento de memória dos ombros do programador.).

CARACTERÍSTICAS DA LINGUAGEM

A linguagem é compilada e interpretada

Principais características e vantagens da linguagem Java:
Suporte à orientação a objetos;
Portabilidade;
Segurança;
Linguagem Simples;
Alta Performance;
Dinamismo;
Interpretada (o compilador pode executar os bytecodes do Java diretamente em qualquer máquina);
Distribuído;
Independente de plataforma;
Tipada (detecta os tipos de variáveis quando declaradas);
Dentro das características, o principal item é o fator da “Independência de plataforma”.
- A independência da plataforma, possibilita o programa ser executado em diferentes plataformas e sistemas operacionais, através de um emulador conhecido como a Máquina Virtual Java ou JVM (Java Virtual Machine), que ajuda rodar os sistemas baseados em Java. É uma máquina virtual baseada em software que é executada dentro dos aparelhos eletrônicos onde irá ler e executar os bytecodes do Java.


CAPACIDADES DA LINGUAGEM

Os critérios de avaliação englobam cinco tópicos (Legibilidade, Capacidade de Escrita, Confiabilidade, Custo e Portabilidade) 
que servem para determinar qual o impacto que a linguagem escolhida trará no projeto e desenvolvimento de um software. 
A linguagem java possui recursos que auxiliam na clareza do código. Java contém instruções de controle necessárias para controlar o fluxo do sistema,
realizando repetições simples.

PRODUTIVIDADE DO DESENVOLVEDOR

Frameworks e Contâiners
Ferramentas Disponíveis
Sintaxe, Semântica e Operações Predefinidas
Legibilidade
Redigibilidade
Custos


ECOSSISTEMA

Maturidade, governança, fragmentação, comunidade.

INFORMAÇÕES ADICIONAIS

1) Capacidade vetorial() Método em Java
O método Java.util.Vector.capacity() em Java é usado para obter a capacidade do Vector ou o comprimento do array presente no Vetor.
Sintaxe: Vector.capacity()
Parâmetros: o método não aceita nenhum parâmetro.
Valor de retorno: o método retorna a capacidade ou o comprimento da matriz de dados interna presente no vetor, que é um valor inteiro.

2) Capacidade de ArrayList
A capacidade inicial padrão de um objeto ArrayList é de 10 elementos.

Após a Oracle anunciar a disponibilidade do Java 17, a versão mais recente da plataforma de desenvolvimento e linguagem de programação,
que é número um do mundo e que oferece milhares de atualizações de desempenho, estabilidade e segurança, 
bem como 14 JEPs (JDK Enhancement Proposals), que melhoram ainda mais a linguagem e a plataforma Java para ajudar os desenvolvedores a serem mais produtivos.
Java 17 é o mais recente lançamento de suporte de longo prazo (LTS) sob a cadência de lançamento de seis meses do Java.
E é o resultado de uma ampla colaboração entre engenheiros da Oracle e outros membros da comunidade mundial de desenvolvedores Java, 
por meio da OpenJDK Community e do Java Community Process (JCP). Desde o lançamento do JDK 11 LTS anterior há três anos, mais de 70 JEPs foram implementados.
Java possibilita aos desenvolvedores: Escrever software em uma plataforma e executá-lo em qualquer outra plataforma, desenvolver aplicativos do lado do servidor,
para fóruns online, lojas, enquetes, processamento de formulários HTML, usar a linguagem Java para criar aplicativos ou serviços altamente personalizados.




