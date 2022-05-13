---
---

#theorem
>👍 [!theorem]+ Theorem: (Darboux)
>Let $(\calP,\omega)$ be a symplectic manifold. Each point $p\in \calP$, has a neighborhood $U$ with coordinate chart $\phi:U\to \CC^n$ such that $\omega$ is the pullback of the standard symplectic form on $\CC^n$. That is, $U$ has coordinates $q_i , p_i$ such that $\omega = \de q_1 \wedge \de p_1 + \dots + \de q_n \wedge \de p_n$

This fact makes symplectic geometry feel significantly different from other sorts of geometry. Compare this with the analagous statement in Riemannian geometry: A metric can be put in the standard, euclidean form *pointwise*, but on an open neighborhood it can diverge from the standard due to its curvature. However, Darboux's theorem says the standard form holds on the whole open est. There are no local invariants of a symplectic form akin to curvature. Said another way, all symplectic forms are locally isomorphic. This gives symplectic geometry a fundamentally globally character, to the point that the names "symplectic geometry" and "symplectic topology" are used interchangably. 

>[!proof]+ Proof
>Moser's trick: Rough ideas
>
>You can find a proof of Darboux's theorem in any book on symplectic geometry (see for instance ==Mcduff==), but to not leave you high and dry, let me give you the gist. We want to show any two symplectic forms on a small open set are equivalent by constructing a symplectomorphism: A diffeomorphisms pulling back one form to the other. (In particular, this can relate the given symplectic form to the standard one). We will instead look for an explicit path of diffeomorphisms, which is infinitesimally encoded in a time-varying vector field. A little manipulation shows this vector field satisfies a differential equation, which in fact is a version of Hamilton's equations. By non-degeneracy, we know a solution to Hamiltons equations exists, and we are done! Though constructing a whole path of diffeomorphisms seems like it would be harder, it lets us exploit the infinitesimal geometry that we know how to manipulate. This bit of slight-of-hand is called *Moser's trick*.  Symplectic geometry has many similar results turning structures into a standard form, all proven with a suitably generalized version of Moser's trick. 
