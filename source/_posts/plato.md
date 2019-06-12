---
title: On Euthyphro
date: 2019-06-11 09:58:55
tags: phil
mathjax: True
---



In Plato's *Euthyphro*, Socrates and Euthyphro discuss the definition of piety, or in Socrates' term, the form itself of piety. <!-- more --> In the dialogue, Socrates makes Euthyphro agree that it is the form itself of piety makes all pious actions pious, which also implies that there is such thing since they do not discuss its existence but directly go to the details of the form itself of piety. Therefore, there is such a premise or agreement between Socrates and Euthyphro, that is, there is such a form itself, or in a more common word, a definition of piety that makes all pious actions pious.

In the following dialogue, Euthyphro gives the first definition of piety:

​    ($1$) What is dear to the gods is pious. (7a)

This definition is quickly challenged since gods may disagree with each other. Socrates makes Euthyphro fix his first definition with a correction:

​    ($2$) What they (the gods) all love is pious. (9d)

This change makes Socrates' previous attack not work, but Socrates still finds another argument against this definition. The argument in the text are based on the following premises:

​    ($3$) It is not being loved by those who love it because it is something loved, but it is something loved because it is being loved by them. (10c)

 It (a pious thing) is being loved then because it is pious for no other reason. (10d)

Socrates then goes to his conclusion:

​    ($5$) The god-loved is not the same as the pious. (10d)

This argument goes too quickly for Euthyphro to understand, and so for some of the readers. Firstly, the meaning of those two premises is not so straight forward since it is in a dialogue, which should be read together with the context. In the second definition, it uses another more familiar concept to define piety, and if we use $x$, $y$, *etc.*, to represent individual variables, and the definition can be read as

​    ($2'$) For every $x$, $x$ is pious if and only if $x$ is loved by all gods.

This definition talks about the relation between being loved by all gods and being pious. However, in the conclusion, it seems that he is talking about another pair of concept. If we correspondingly read that proposition, it can be

​    ($5'$) It is not the case that for any $x$, $x$ is god-loved if and only if $x$ is pious.

The word "god-loved" can be reduced to a more basic phrase

​    ($5''$) It is not the case that for every $x$, $x$ is loved by (all) gods if and only if $x$ is pious.

The quantifier "all" can be added from the context. Next, we check the first premise, which can also be read as the conjunction of the following two propositions:

​    ($3.1$) For every $x$ and $y$, it is not the case that $x$ is being loved by $y$ because $x$ is something loved by $y$.

​    ($3.2$) For every and $y$, $x$ is something loved by $y$ because $x$ is being loved by $y$.

Here, Socrates makes an explicit distinction between being loved and being something loved. Therefore, the phrase "the god-loved" should be read as "something loved by all gods", not like in the previous one, and so for "the pious". Therefore, we should read the definition as

​    ($2''$) For every $x$, $x$ is something pious if and only if $x$ is something loved by all gods.

And the conclusion should be read consistently as

​    ($5'''$) It is not the case that for every $x$, $x$ is something loved by all gods if and only if $x$ is something pious.

Similarly, the second premise can also be written as the conjunction of the following two propositions:

​    ($4.1$) For every $x$ satisfying that $x$ is something pious, $x$ is being loved by all gods because $x$ is something pious.

​    ($4.2$) For every $x$ satisfying that $x$ is something pious, it is not the case that $x$ is being loved by all gods for any reason other than $x$ is something pious.

In the following argument, Socrates derives a proposition from ($3.2$), which only restricts the range of $y$:

​    ($6$) For every $x$, $x$ is something loved by all gods because $x$ is being loved by all gods.

This derivation is sound for most people who familiar with the relation of sets, but his next proposition is not clear as the previous one. He claims that a pious thing is not pious because it is being loved (10e). More formally, we require the following proposition:

​    ($7$) For every $x$ satisfying that $x$ is something pious, it is not the case that $x$ is something pious because $x$ is being loved by all gods.

Socrates argues that this should be derived from the second premise. However, by using "being loved by all gods" as a specific "other reason" to give a detailed instance of the ($4.2$), the proposition should be

​    ($8$) For every $x$ satisfying that $x$ is something pious, it is not the case that $x$ is being loved by all gods because $x$ is being loved by all gods.

To reach Socrates' proposition, besides the definition, we need another proposition:

​    ($9$) For every $x$, $x$ is being loved by all gods if and only if $x$ is something loved by all gods.

These propositions are valid for every person if she uses English correctly, and therefore, Socrates' that proposition can be derived from (8), (9) and ($5''$). If ($6$) and ($7$) are both true, from them we have

​    ($10$) For every $x$ satisfying that $x$ is something pious, $x$ is something loved by all gods because $x$ is being loved by all gods and it is not the case that $x$ is something pious because $x$ is being loved by all gods.

Substitute the last occurrence of "pious" with "loved by all gods" by using the definition, we have

​    ($11$) For every $x$ satisfying that $x$ is something pious, $x$ is something loved by all gods because $x$ is being loved by all gods and it is not the case that $x$ is something loved by all gods because $x$ is being loved by all gods.

That is a contradiction if there indeed is something pious, which is guaranteed at the very beginning as a basic agreement between Euthyphro and Socrates. Hence, if all Socrates' premises and ($9$) are true, then Euthyphro's second definition of piety must be false.

However, in this argument, the derivation of proposition ($8$) may have some problems. In the derivation from the second premise to ($8$), we require a reason other than being pious, which means that "$x$ is being loved by all gods", and "$x$ is being pious" should be different. However, the word "other" or "different" can have various readings. For instance, it cannot be a relation about spelling, since it will make the premise too strong. However, if Euthyphro's definition holds, then "$x$ is being loved by all gods", and "$x$ is being pious" should be the same in terms of truth condition. And in this case, we cannot get ($8$) from the second premise, and hence, the reductio ad absurdum showed above is not sound.

Another possible issue is about the conjuncture "if and only if" ("iff" for short) and "because". In the previous discussion, when we say that "$P$ iff $Q$", where $P$ and $Q$ are propositions, we factually suggest a substitutability about propositions, *i. e.*, for every proposition $A(X)$, if $A(P)$ holds so are $A(Q)$, and we used this in the derivation from ($8$) to ($7$), and ($10$) to ($11$). Then substitutability seems to be a reasonable property if we want to have a definition, as Socrates does, but for other cases, it is possible that we have some case when "iff" have no substitutability. For instance, in ($6$), we cannot substitute "something loved by all gods" with "being loved by all gods" by using ($9$) and its substitutability, since in that way we get

​    ($12$) For every $x$, $x$ is being loved by all gods because $x$ is being loved by all gods.

That seems not to be a correct way to use "because". Similarly, we cannot substitute "being loved by all gods" with "something loved by all gods" in that case. These facts at least indicate that we cannot always perform such a substitution to a proposition containing "because" by using some "iff"-proposition like ($9$), no matter the occurrence of proposition we want to substitute in is at which side of "because". Therefore, the argument is unsound. Factually, we can also reach ($11$) without ($7$). We can derive ($8$) from the second premise, and get the following proposition from ($8$) and ($9$) with a substitution:

​    ($13$) For every $x$ satisfying that $x$ is something pious, it is not the case that $x$ is something loved by all gods because $x$ is being loved by all gods.

And then we can also reach ($11$). The main problem here seems to be the substitutability of ($9$). However, even when "iff" represent a definition, the substitutability is still doubtful. Consider this case: if $P$ iff $Q$ holds, then $Q$ iff $P$ because $P$ iff $Q$ also holds, but it is not the case that $Q$ iff $P$ because $Q$ iff $Q$, nor $Q$ iff $Q$ because $P$ iff $Q$. The conjuncture "because" is the main factor for casing our substitutability for propositional logic not holds anymore, which is used in Socrates' argument.