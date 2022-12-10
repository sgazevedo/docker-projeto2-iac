# Definição de um Cluster Swarm Local com o Vagrant

Nesse repositório estão contidos os códigos de um dos desafios ocorridos no curso de Docker, parte do Bootcamp **"Jornada DevOps com AWS - Impulso"**, organizada pelo portal [DIO](https://www.dio.me/), no período de outubro a dezembro de 2022. 

## Descrição
Neste desafio de projeto iremos criar um Cluster Swarm local, utilizando máquinas virtuais, além, de aplicar nossos conhecimentos em Vagrant. Também vamos aprender uma forma de evitar as implementações manualmente, melhorando o desempenho dos desenvolvedores.

### Definições
* Criar um Vagrantfile com as definições de 4 máquinas virtuais. Sendo uma máquina com o nome de master e as outras com os nomes de node01, node02 e node03; 
* Cada máquina virtual deverá ter um IP fixo; 
* Todas as MV deverão possuir o Docker pré-instalado; 
* A máquina com o nome de master deverá ser o nó manager do cluster. 
* As demais máquinas deverão ser incluídas no cluster Swarm como Workers. 
