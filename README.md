# Incomplete Num Instance for Maybe Monad

This repository demonstrates a subtle bug related to an incomplete instance declaration of the `Num` typeclass for the `Maybe` monad in Haskell. The provided code implements addition, subtraction, and multiplication for `Maybe` values, but lacks proper handling for edge cases, leading to unexpected behavior or even crashes in specific scenarios.

The `bug.hs` file contains the buggy code. The `bugSolution.hs` file provides a corrected version with a more comprehensive and robust implementation of the `Num` typeclass instance for the `Maybe` monad, addressing the edge cases properly.

The bug is particularly interesting for its subtlety; it highlights the importance of thorough testing and complete instance declarations when working with typeclasses in Haskell.  Understanding this bug provides insights into the complexities of monads and typeclasses.