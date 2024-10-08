## Description
The very first PR of the project formalizing core concepts and results in auction theory.
Our group is working on more contributions on the formalization of gamtheory perfix. 

Authored-by: 
- Ma Jiajun <hoxide@gmail.com>;
- Wang Haocheng <hcwang942@gmail.com>;
- Zhang Xinyuan
- Wang Xuhui

## Current plan for formalization of Game Theory
The current plan for the formalizing of Game Theory include:
#### 1. Auction Theory. 🎉   _(200+ lines, PR)_ [link](https://github.com/leanprover-community/mathlib4/pull/13248)
- Essential definitions of Sealed-bid auction, First-price auction and Second-price auction.
- First-price auction has no dominant strategy.
- Second-price auction has dominant strategy. (Second-price auction is DSIC)
- [x] _Will depend on #14163 once that PR is merged. The Fintype lemmas introduced by this PR have been added in that PR and will be removed from here once that PR gets merged_

#### 2. Mechanism design & Myerson's Lemma.    🎉 _(400+ lines, pending for modification to Mathlib Standard)_
-  Mechanism design
An allocation rule is implementable if there exists 
        - Dominant Strategy Incentive Compatible (DSIC) payment rule
        - An allocation rule is monotone if for every bidder’s gain is nondecreasing w.r.t. her/his bid
- Myerson's Lemma
                Implementable ⇔ Monotone
                In the above case, the DSIC payment rule is unique.                                     
#### 3. von Neumann‘s Minimax Theorem. 🎉 _(800+ lines, pending for modification to Mathlib Standard)_
- Equilibrium in zero sum game
- Formalization strategy: via Loomis’s theorem.
#### 4. Nash Equilibrium. 🎉 _(pending for modification to Mathlib Standard)_
    
#### 5. Brouwer fixed-point theorem. _(Work in Progress)_
#### 6. More Mechanism design._(Planning)_

## Reference
Roughgarden, Tim. ***Twenty Lectures on Algorithmic Game Theory***. Cambridge University Press, 2020. [Link](https://www.cambridge.org/core/books/twenty-lectures-on-algorithmic-game-theory/A9D9427C8F43E7DAEF8C702755B6D72B)

