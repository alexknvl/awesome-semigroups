# awesome-semigroups
Awesome computationally efficient semigroups. At the moment this repository serves as a collection of useful semigroups I could use for hashing. See https://alexknvl.com/posts/monoidal-hashing.html for some background.

## Abelian groups
1. Addition on `Int`, `Long`, etc.
   * Can be mod `p` for any `p` as well.
2. Multiplication on `Int`, `Long`, etc, excluding the zero.
   * Can be mod `p` for any prime `p`.
3. Addition on matrices.

## Non-commutative monoids with annihilators
1. `(a, b) |+| (c, d) = (a + b * c, b * d)`. 
   * `(0, 0)` is a left annihilator. 
   * `(0, 1)` is an identity element.
   * Can be mod `p` for any prime `p`.

## Non-commutative monoids without annihilators
1. [Special linear group](https://en.wikipedia.org/wiki/Special_linear_group)
2. [General linear group](https://en.wikipedia.org/wiki/General_linear_group)
