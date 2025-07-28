# Desafio de Projeto: Abstraindo um Bootcamp Usando Orientação a Objetos em Java

Este projeto foi desenvolvido como parte do desafio proposto pela Digital Innovation One (DIO), com o objetivo de reforçar os pilares da Programação Orientada a Objetos (POO) com Java: **Abstração, Encapsulamento, Herança e Polimorfismo**.

## 🧰 Tecnologias e Ferramentas

- Java 21 (JDK)
- Gradle (Build Tool)
- Lombok (para reduzir verbosidade do código)
- IntelliJ IDEA (ou qualquer IDE compatível com Gradle)

## 📁 Estrutura do Projeto

O projeto segue a estrutura padrão de projetos Gradle em Java:

desafio-poo-dio/
├── build.gradle
├── settings.gradle
└── src/
└── main/
└── java/
└── br/
└── com/
└── dio/
└── desafio/
├── Main.java
└── dominio/
├── Bootcamp.java
├── Curso.java
├── Dev.java
└── Mentoria.java


> ⚠️ A estrutura correta é essencial para que o Gradle reconheça os arquivos e permita a execução da aplicação. A classe `Main` deve estar dentro do pacote `br.com.dio.desafio`.

## ⚙️ Execução do Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo

2. Executar com Gradle
Via terminal:

bash
Copiar
Editar
./gradlew run
Ou via IntelliJ IDEA:

Aguarde o carregamento do Gradle (ícone do elefante)

Abra Main.java

Clique no botão verde de execução (▶️)

A aplicação irá exibir no terminal as informações dos Devs, cursos, mentorias e progresso dentro do bootcamp.

✅ Melhorias Aplicadas
✅ Uso do Gradle como sistema de build

✅ Uso do plugin de aplicação no build.gradle

✅ Inclusão do Lombok para gerar automaticamente getters, setters, toString, equals, hashCode, e construtores

✅ Organização do código-fonte em pacotes (br.com.dio.desafio e dominio)

✅ Estrutura de pastas padronizada conforme boas práticas (src/main/java)

✅ Código modularizado, limpo e pronto para evoluções futuras
```

## 🧠 Conceitos Abordados
Programação Orientada a Objetos (POO)

Abstração de entidades do mundo real

Encapsulamento de atributos e comportamentos


## Desenvolvido com dedicação para fins educacionais.

Herança entre classes (Curso e Mentoria herdam de Conteudo)

Polimorfismo com métodos sobrepostos e coleções genéricas

