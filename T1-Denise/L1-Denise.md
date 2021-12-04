L1 C++

Histórico e apresentação.

O C++ foi inicialmente desenvolvido por Bjarne Stroustrup dos Bell Labs, durante a década de 1980 com o objetivo
implementar uma versão distribuída do núcleo Unix.[4] Como o Unix era escrito em C, deveria-se manter a compatibilidade, ainda que adicionando novos recursos.
c++ surgiu em 1979 e foi padronizada em 1998.
É uma linguagem de programação compilada, multi-paradigma (seu suporte inclui linguagem imperativa, orientada a objetos e genérica) e de uso geral. 
Paradigma: orientada a objetos · genérica · procedural

Conceitos: É uma linguagem de programação compilada, exemplo de código simples que imprime Alô, Mundo! :
#include <iostream>
int main() {
    std::cout << "Hello World!";
    return 0;
}

C++ possui métodos estáticos. Exemplo de código contendo uma classe com dois métodos estáticos, sendo que o primeiro chama o segundo.
class Exemplo{
        public:
           static void metodo1(){
                 metodo2();
            }
            static void metodo2(){
                std::cout<<"Alo mundo"<<std::endl;
            }
    };

IDES: Code::Blocks, Dev C++ e Eclipse, Code::Blocks, CodeLite, C++ Builder, GNAT Programming Studio, Netbeans, Qt Creator.
Alguns aplicativos conhecidos que já foram desenvolvidos em C++:  Adobe Photoshop, BrOffice, Internet Explorer, Mozilla Firefox, Winamp

Possui a noção de pacotes, É preciso criar um namespace, um arquivo 
cabeçalho .h e um arquivo .cpp. No cabeçalho declarar a classe e seus métodos dentro do namespace e no .cpp a implementação dos métodos também dentro do namespace. 
Então, no arquivo onde a classe será usada, incluir o .h e usar o namespace criado. 

Convenções usadas para nomear classes: Upper camel case

Convenções usadas para nomear métodos: Lower camel case

A biblioteca cstdarg permite trabalhar com funções de números variáveis de parâmetros. cstdarg é a versão em C++ da biblioteca stdarg em C.

Visibilidade: C++, Possui mecanismos para controlar o acesso (visibilidade) a métodos e atributos de uma classe.

O gerenciamento de memória: É explícito.

Referências:
- Tipos: possui tipos primitivos;
- Palavra-chave usada para denotar uma referência nula: null;
Precedência e capacidade de associação: A precedência do operador especifica a ordem das operações em expressões que contêm mais de um operador. A associatividade do operador especifica se, em uma expressão que contém vários operadores com a mesma precedência, um operand é agrupado com o à esquerda ou o à direita.



Características da linguagem. 

Mais características do C++:
Possibilidade em programação de alto e baixo nível
É padronizado pela ISO
Compatibilidade com a linguagem C
Possui paradigmas de programação funcional, genérica, orientada a objetos e imperativa
Pode ser ser utilizada sem a necessidade de um ambiente de desenvolvimento sofisticado



Capacidade da linguagem. 
C++ é uma linguagem de programação multiplataforma, multi-paradigma e de médio nível, isto é, 
combina características de linguagens de alto e baixo níveis. É uma das linguagens mais populares do mundo.

produtividade do desenvolvedor.

Os desenvolvedores do C++Builder relatam que podem fornecer aplicativos do conceito à implantação 5x mais rápido do que com outras ferramentas 
- e chegar ao mercado muito mais rápido significa valor direto para sua empresa.
Classes/Bibliotecas Robustas construídas, para desenvolvedores,que contribuem para tornar o desenvolvedor,  mais produtivo

Ecossistema
Frameworks 
Ferramentas Disponíveis
Sintaxe, Semântica.

Informações Adicionais
O C++ tem sido usado para construir inúmeras bibliotecas principais muito populares, aplicativos como o Microsoft Office,
motores de jogos como Unreal, ferramentas de software como o Adobe Photoshop, compiladores como clang, bancos de dados como o MySQL
e até sistemas operacionais como o Windows em uma ampla variedade de plataformas à medida que continua a evoluir e crescer.



Referências:  L1 C++

1- C++ Programming - The State of Developer Ecosystem in 2021 Infographic | JetBrains: Developer Tools for Professionals and Teams
2- Por que C++Builder - C++Builder - Products - Embarcadero Website
3- C++ quadros, benefícios e recomendações | Webinars Abertos (openwebinars.net)
4- Ferramentas e funcionalidades do C++ em edições do Visual Studio | Microsoft Docs
5-Ecossistema C++: Compiladores, IDEs, Ferramentas, Testes e Muito Mais - Histórias C++ (cppstories.com) 
6- https://www.devmedia.com.br/historia-do-c-c/24029
7- https://acervolima.com/historia-do-c/




Referências: L2 Java

1- Guia Completo de Java: Aprenda a Linguagem de Programação Java (devmedia.com.br)
2- Java: história e principais conceitos (devmedia.com.br)
3- java_basico.pdf (unisinos.br)
4- LINGUAGEM JAVA E SUAS CARACTERÍSTICAS - JDEV Treinamento
5- Polimorfismo • Universidade Java 1-
6- Capacidade vetorial() Método em Java – Acervo Lima
7- Java/ArrayList - Wikilivros (wikibooks.org)
8- java_intro.pdf (uminho.pt)
9- Como adicionar capacidades de refazer e desfazer a um JTextArea (arquivodecodigos.com.br)
10- Por que a capacidade máxima de um Java HashMap 1 é << 30 e não 1 << 31? - java, hashmap, capacidade (living-sun.com)
11- Oracle lança o Java 17



