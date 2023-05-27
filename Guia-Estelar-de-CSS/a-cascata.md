# A cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.

* Seu estilo é lido de cima para baixo.

É levado  em consideraçãoa 3 fatores

1. Origem do estilo
2. Especificidade
3. Impotância

### Origem do estilo

inline > tag style > tag link

### Especificidade

É um cálculo matemáttico, onde cada tipo de seletor e origem de estilo, possuem valores a serem considderados.

0. Universal selector, combinatores  e negation  pseudo-class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e attribute selectors ([type="radio"])
100. ID selector
1000. Inline

### A regra important!

* cuidado, evite o us
* não é considerado uma boa prática
* quebra o fluxo natural da cascata

