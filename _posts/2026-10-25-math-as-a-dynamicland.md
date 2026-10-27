---
layout: post
title: "Math as a Dynamicland"
date: 2026-10-25
categories: jekyll update
---

I'd say math is some kind of Dynamicland, in the sense that it is part of the fabric of reality, to make sense of reality itself. For example, when you read *Nonlinear Dynamics and Chaos* by Steven Strogatz, he introduces some mathematical ideas to precisely capture nonlinear movements. I think he calls them deterministic mechanisms that are unpredictable: the movements are produced by some deterministic mechanism, but you cannot predict how it's going to move. That is something that really blew his mind, and he wanted to investigate it further. One concept he introduces is phase space, which basically lays open the entire behavior of that system, to put it in a vague way.

Another example is the Dihedron algebra, which has some non-obvious ideas that only emerge after you spend weeks thinking in it and watching what people do with it. The dual numbers live inside this algebra, and it's the environment the complex numbers are born from. When you dig around in it, the complex numbers simply fall out, because they're a sub-algebra.

Or, for example, when you compare that algebra with the algebra of polynomials that are modulo x + 1, you can see that they are isomorphic.

To come back to the dual numbers: they are of the form α + βε. What Wildberger did was put that into a polynomial, p(a + bε) with p = αⁿ. Then you get the expression (a + bε)ⁿ, and after applying the binomial expansion and some algebraic manipulations and simplifications, you can see how the derivative falls out of it.

If p = αⁿ, then

$$
p(a+b\varepsilon) = (a+b\varepsilon)^n = a^n + \binom{n}{1}a^{n-1}b\varepsilon + \binom{n}{2}a^{n-2}(b\varepsilon)^2 + \cdots + (b\varepsilon)^n
$$

and since ε² = 0, we have

$$
p(a+b\varepsilon) = \underbrace{a^n}_{p(a)} + \underbrace{n a^{n-1}b\varepsilon}_{Dp(a)}
$$

So math can be a breeding ground for new math when you play around in it,{% include sidenote.html id="sn-wigner" text="Mathematicians have marveled at versions of this for a long time; Wigner’s “unreasonable effectiveness” is the outward-facing version, and mine is the inward-facing one." %} and the math provides you with tools to investigate the math itself. It's like this unfolding process, right? You create the sense-making environment as you're making sense of the math, and reality gives you the tools to do that. Isn't that completely nuts? And Dynamicland is this very meta-environment, which promises to let you make sense of the math in Dynamicland. It tries to be the most general environment where ideas become physical, shared, and directly manipulable in a room with other people.
