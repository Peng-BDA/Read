# 2. Ordinal Games in Strategic Form

## Game Frame

**Game Frame Definition**
A game-frame in stratefic form is a list of four items <I, (S1, S2, ..., Sn), O, f> where:
* I = <1, 2, ..., n> is a set of players (n $\geq$ 2).
* (S1, S2,...,Sn) is a list of strategic profile sets. FOr every Player i $\in$, Si is the set of Strategies of Player i. Denote S the Cartesian product of these sets: S = S1 $\times$ S2 $\times$ ... $\times$ Sn; We call S the set of strategy profiles
* O is a set of outcomes. An element of S is a list s = (s1, s2,..., sn) consisting of one strategy for each Player.
* f: S $\rightarrow$ is a function that associates with every strategy profile s an outcome f(s) $\in$ O.

We can utility function U(o) to represent the ranking.

**Reduced-form game**

|           |                | Player 2  |  |
|--         | ------------- |------------- | ------------- |
|           |               |Split  | Steal  |
| Player 1  |        Split  |4 3   | 2 4  |
| 		      | Steal         |3  2  | 1 2  |

## Strict and weak dominance

**Strict and weak dominance Definition**
* a strictly dominates b if, in very situation, a gives Player i a payoff which is greater than the payoff that b gives. Formally: for every $s_{-i} \in S{-i}, \pi_i(a, s_{-i} > \pi_i(b, s_{b, -i})$.
* a weakly dominates b if, in very situation, a gives Player i a payoff which is greater than or equal to the payoff that b gives and furthermore, there is at least one situation where a gives a better payoff than b. Formally:
  for every $s_{-i} \in S{-i}, \pi_i(a, s_{-i} \geq \pi_i(b, s_{b, -i})$ and there exist an  $s_{-i} \in S{-i}, \pi_i(a, s_{-i} > \pi_i(b, s_{b, -i})$.
* a is equivalent to b if, in very situation, a and b gives Player i the same payoff. Formally: for every $s_{-i} \in S{-i}, \pi_i(a, s_{-i} = \pi_i(b, s_{b, -i})$.

**stricyly and weakly dominant strategy**
* a is a strictly dominant strategy if a strictly dominates every other strategy of Player i.
* a is a weakly dominant strategy if, for every other strategy x of Player i, one of the following is true: either (1) a weakly dominates x or (2) a  is equivalent to x.

**strategy profile**
Givne an ordinal game in strategic form, let $s = (s_1,..., s_n)$ be a strategy profile. We say that
* a is a strict dominant strategy profile, if every Player i, $s_i$ is a strictly-dominant strategy.
* a is a weak dominant strategy profile, if every Player i, $s_i$ is a weakly-dominant strategy and, furthermore, for at least one Player j, $s_j$ is not a strictly-dominant strategy.

**Pareto superior**
We say that o is strictly Pareto superior to $o^{'}$ if every player prefers o to $o^{'}$ (that is, if $o >_i o^{'}$, for every Player i) and weakly pareto superior if $o \geq_i o^{'}$, for every Player i and there is a Player j such that $o >_i o^{'}$.

## Second-price auction
**Theorem - Vickrey, 1961**
In a second-price auction, if Player i is selfish and greedy then it is a weakly dominant strategy for Player i to bid her true value, that is, to choose $b_i=v_i$.

  
