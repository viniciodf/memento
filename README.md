Padroes de Projeto

1) Criacionais -> Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.
2) Estruturais -> Os padrões estruturais explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
3) Comportamentais -> Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos.

* Comportamentais

5.Memento

O que é:
O Memento é um padrão de projeto comportamental que permite tirar um “retrato” do estado de um objeto e restaurá-lo no futuro.

Aplicabilidade:
Utilize o padrão Memento quando você quer produzir retratos do estado de um objeto para ser capaz de restaurar um estado anterior do objeto.
Utilize o padrão quando o acesso direto para os campos/getters/setters de um objeto viola seu encapsulamento.

Exempos de utilizacao:
java.io.Serializable
javax.faces.component.StateHolder