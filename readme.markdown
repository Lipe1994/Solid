### Solid
##### Solid é são o conjunto de 5 princípios que todo programador que trabalha com OO deveria saber.

Este resumo é uma maneira que eu tenho de estudar conceitos e ao mesmo tempo compartilhar meus novos conhecimentos no GitHub.

Solid são 5 princípios de programação orientada a objetos que facilitam o desenvolvimento de software, tornando-os fáceis de manter e estender.
O acrônimo "Solid", foi criado por Michael Feathers, após observar os 5 princípios da orientação a objetos e design de código criados por Rober C. Martim(Famoso Uncle Bob).

### S.P.L.I.D
- S single responsibility principle (SRP)
- O Open-Close Principle (OCP)
- L liskov substitution principle (LSP)
- I interface segregation principle (LSP)
- D Dependence Inversion Principle (DIP)

SRP => Principio da responsabilidade única, diz que "Uma classe deve ter um, e somente um, motivo para mudar". Este principio declara que uma classe deve especializada em um único assunto e possuir apensas uma responsabilidade no software.

OCP => Princípio aberto fechado, alega "Objetos ou entidades devem estar abertos para extensão, mas fechados para modificação". Este Princípio sugere o uso de abstração, herança ou extensão para colocar novas funções em uma entidade.

LSP => Princípio da substituição de Liskov, Uma classe derivada deve ser substituível por sua classe base, na minha visão este princípio sugere que uma classe A que herde a classe B, seja substituível pela classe B porém sem causar modificações nos dados mesmo que a classe B tenha menos dados que a A(mais mantenha a integridade do que tiver de dados).

![Example](https://github.com/Lipe1994/Solid/blob/master/example.png)