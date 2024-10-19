# 2. Ordinal Games in Strategic Form

## Game Frame Definition

A game-frame in stratefic form is a list of four items <I, (S1, S2, ..., Sn), O, f> where:
* I = <1, 2, ..., n> is a set of players (n $\geq$ 2).
* (S1, S2,...,Sn) is a list of strategic profile sets. FOr every Player i $\in$, Si is the set of Strategies of Player i. Denote S the Cartesian product of these sets: S = S1 $\times$ S2 $\times$ ... $\times$ Sn; We call S the set of strategy profiles
* O is a set of outcomes. An element of S is a list s = (s1, s2,..., sn) consisting of one strategy for each Player.
* f: S $\rightarrow$ is a function that associates with every strategy profile s an outcome f(s) $\in$ O.

We can utility function U(o) to represent the ranking.

## Reduced-form game

|           |                | Player 2  |  |
|--         | ------------- |------------- | ------------- |
|           |               |Split  | Steal  |
| Player 1  |        Split  |4 3   | 2 4  |
| 		      | Steal         |3  2  | 1 2  |

## Strict and weak dominance Definition

* a strictly dominates b if, in very situation, a gives Player i a payoff which is greater than the payoff that b gives. Formally: for every $s_{-i} \in S{-i}, \pi_i(a, s_{-i} > \pi_i(b, s_{b, -i})$.
* a weakly dominates b if, in very situation, a gives Player i a payoff which is greater than or equal to the payoff that b gives and furthermore, there is at least one situation where a gives a better payoff than b. Formally:
  for every $s_{-i} \in S{-i}, \pi_i(a, s_{-i} \geq \pi_i(b, s_{b, -i})$ and there exist an  $s_{-i} \in S{-i}, \pi_i(a, s_{-i} > \pi_i(b, s_{b, -i})$.
