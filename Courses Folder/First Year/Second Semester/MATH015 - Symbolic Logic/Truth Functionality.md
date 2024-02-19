# Truth Functionality of Logical Connectives
## Truth Functionality
Logical connectives can combine the truth values of two propositions.
- Different logical connectives have different rules on how they combine truth values
- These rules are called **truth functionality**

Here are some examples of the truth functionality of basic [[Logical Connectives|logical connectives]]:
- **Conjunction** - $p \wedge q$ is **1** if *both propositions* are 1
- **Disjunction** - $p \vee q$ is **1** if *at least one proposition* is 1
- **Negation** - $\neg p$ is **1** only if $p$ is 0, and vice-versa
- **Conditional Connective** - $p \rightarrow q$ is **0** only when the antecedent is 1 and the consequent is 0

Another logical connective in which the disjunction is indefinite when both $p$ and $q$ are true called the **exclusive-or* (exor)*
- $p \oplus q$ is 1 when *exactly one proposition is 1*

## Truth Table
Truth table is a tool used in logic in analyzing the *truth value of compound proposition* at different *combinations* of the *truth value* of its simple proposition

Here are some examples of truth tables of logical connectives

![[Pasted image 20240219175018.png]]

Using the truth table we can classify compound propositions according to their truth value.
- **Tautology** - ==The  compound proposition is **always 1**== regardless of the truth value of the propositional variables
- **Contradiction** - ==The compound proposition is **always 0**== at any combination of truth value of propositional variables
- **Contingent** - ==The compound proposition is **neither tautology nor contradiction**==

### Suggestions in Constructing Truth Tables
1. Construct an initial table with $n$ columns and $2^n$ rows, where $n$ is the number of propositional variables.
	- Write the variables in the column header alphabetically

2. Write alternating 1s and 0s in each column. ==The alternation for column $i$ is $2^{n-i}$ or $\frac{2^n}{2^i}$==

3. Add one column in the initial table for each logical connective in the given
	- Last column must be the truth value of the given compound proposition

4. Write 1s and 0s in each column based on the logical connective of the compound proposition assigned in the column

![[Pasted image 20240219180501.png]]

![[Pasted image 20240219180524.png]]

![[Pasted image 20240219180540.png]]
