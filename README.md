# Sistema de Xadrez

# Sobre o projeto

chess-system-java é um simulador de partidas de xadrez feito em Java, nele o usuário escolhe a peça que deseja movimentar informando
a coluna e a linha em que a peça se encontra (exempo: b2), em seguida o sistema fornece os possíveis movimentos que a peça pode fazer
(marcados em azul), desta foorma o usuário pode decidir para qual casa a peça irá se mover (informando a coluna e a linha).

## ⚙️ Requisitos

- Java 21
- Git Bash
- Maven*  

Abaixo segue uma imagem do sistema rodando no Git Bash:

<img width="628" height="972" alt="image" src="https://github.com/user-attachments/assets/91be88d4-d662-477d-bb65-b597e7bbfc83" />

# Como executar o projeto

- clonar repositório:  
  git clone https://github.com/Marco-Antonio-de-Castro-Damasceno/chess-system-java  
- entrar na pasta do projeto:   
  cd chess-system-java
- compilando o projeto:  
  mvn clean install
- rodar o projeto:  
  mvn exec:java -Dexec.mainClass="applications.Program"
