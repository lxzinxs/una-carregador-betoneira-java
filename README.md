# 🏗️ Simulador de Carregamento de Betoneira

Este projeto é uma aplicação de console desenvolvida em **Java** que simula o processo de carregamento de agregados (Brita 1) em uma betoneira industrial. O foco do exercício é praticar estruturas de repetição, condicionais e lógica de controle de peso.

---

## 🔍 Visão Geral do Exercício

O objetivo é atingir uma meta de peso específica através de ciclos de adições manuais. O sistema monitora o peso atual em tempo real e valida se o carregamento final está dentro de uma margem de segurança aceitável para garantir a estabilidade do equipamento.

---

## 🎮 Funcionalidades

O simulador executa as seguintes etapas:

1. **Definição de Meta**: O sistema estabelece um objetivo de carga fixa (500kg).
2. **Ciclo de Carregamento**: Utiliza uma estrutura `do-while` para solicitar repetidamente a inserção de peso até que a meta seja atingida ou ultrapassada.
3. **Contagem de Ciclos**: Monitora e informa em quantos ciclos o usuário conseguiu atingir a meta.
4. **Validação de Segurança**:
   * Verifica se o peso final excedeu o limite de segurança de 5% acima da meta.
   * Emite alertas de instabilidade caso a meta seja ultrapassada significativamente.

---

## 🛠️ Detalhes Técnicos

* **Linguagem**: Java.
* **Entrada de Dados**: Classe `Scanner` para interação via terminal.
* **Lógica de Controle**: 
  * Estrutura `do-while` para o loop de carregamento contínuo.
  * Condicionais `if/else` para validação de margem de erro e segurança.
  * Uso de acumuladores para somar o peso adicionado a cada ciclo.

---

## 🚀 Como Executar

1. Certifique-se de ter o **JDK** instalado em sua máquina.
2. Compile o arquivo:
   ```bash
   javac SimuladorBetoneira.java
3. Execute a aplicação:
   ```bash
   java SimuladorBetoneira

---

**Desenvolvido por Lucas Nery Miranda**
*Estudante de Ciência da Computação - UNA*
