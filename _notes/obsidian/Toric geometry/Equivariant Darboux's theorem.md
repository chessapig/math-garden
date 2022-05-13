---
---

#theorem
>[!theorem]+ Theorem: Equivariant Darboux's theorem
>Let $(\calP,\omega)$ be a symplectic manifold with $U(1)$ action defined by moment map $\mu$. Each fixed point of the $U(1)$ action has a neighborhood $U$ equivalent to $(\CC^n,\omega_{\textrm{s}})$ with $U(1)$ action defined by moment map 
>$$H_{\vec{\lambda}} = \lambda_1||z_1||^2 + \dots + \lambda_{n}||z_n||^2 \qquad \vec{\lambda} \in \ZZ^n$$
>That is, there is a there is a symplectomorphism $\phi:(U,\omega) \to (\CC^n,\omega_{\textrm{standard})}$ such that $\mu = H_{\vec{\lambda}} \circ \phi$


Just like symplectic manifolds are modeled on phase space (Darboux's theorem, [[Darboux's theorem]]), symplectic manifolds with circle actions are modeled on harmonic oscillators. 

This says that the neighborhood of a fixed point is equivalent to a harmonic oscillator, characterized by a weight vector $\vec{\lambda}$. Note that the equality of the moment maps implies the $U(1)$ actions are intertwined. If the flow under $\mu$ is $\rho_t$ and the flow under $H_{\vec{\lambda}}$ is $\rho^{\textrm{HO}}_t$, then $\phi \circ \rho_t = \rho^{\textrm{HO}}_t \circ \phi$. 

>[!proof]+ proof
>The proof is a modification of the proof of vanilla [[Darboux's theorem]]. It uses an equivariant version of Moser's trick.

This is significant in a similar way to Darboux's theorem. You would expect something like this to be true only infetesimally, i.e on the level of the linearized $U(1)$ aciton on the tangent space. Indeed, this is the case for the equvilent statement in Riemannian geometry. But, the rigidity of symplectic geometry extends this linear action exactly to a whole nieghborhood of the fixed point. This makes the behievor at the fixed points somewhat *global*. The quadradic charecter of the moment map (the defining proprety of a harmonic osscilator Hamiltonian, and the reason that the $U(1)$ action is linear) also extends globally. The $U(1)$ action on $\calP$ is ultimatly almost completly charecterized by the collection of harmonic osscilators at each of the $U(1)$ fixed points. 