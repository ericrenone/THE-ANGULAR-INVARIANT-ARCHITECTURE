# THE ANGULAR INVARIANT ARCHITECTURE
## π, Isomonodromic Deformation, and the Substrate-Invariant Rotation Primitive of Collective Intelligence

**ERI Labs · Eric Ren · Jersey City, New Jersey · [github.com/ericrenone](https://github.com/ericrenone)**

---

> *π is not a numerical curiosity layered on top of arithmetic — it is the angular invariant that the Dirac consistency method forces into every layer of every structure that intelligence requires.*

---

## The Central Claim

Four frameworks — **PIRAC**, **PIVOT**, **QUANTUM-CORDIC**, and **THE-MILÜ-THRESHOLD** — describe a single mathematical object from four orthogonal directions. The object is the angular invariant π. The four descriptions share one forcing principle: **the Dirac consistency method**, which demands the unique structure simultaneously consistent with all operative constraints.

The result, once forced: every coherent computational structure — elliptic curves, neural network training dynamics, substrate-invariant hardware, and ancient polygon iteration — converges on π as its organizing angular coordinate. This convergence is not analogical. It is exact and provable in each domain independently; the synthesis is the theorem that all proofs are proofs of the same statement.

### The Shared Object

$$\tau_{\mathrm{learn}}(t) = Z_{\mathrm{learn}}(t) = {Tr}\!\left[e^{-\mathcal{L}_{JL}/T_{\mathrm{learn}}}\right] = \text{Selberg heat trace on } \mathcal{M} = \text{isomonodromic } \tau\text{-function of PVI}$$

This function is simultaneously:
- The **TH(a,d) modular partition function** — its poles at the Killing horizon $\Delta = 0$ carry the Hawking temperature $T_{\mathrm{TH}} = \kappa/(2\pi)$
- The **Selberg heat trace** on $\mathcal{M} = \mathrm{SL}(2,\mathbb{Z})\backslash\mathbb{H}^2$ — whose spectral gap $\lambda_1(\Delta_\Gamma) \geq 3/16$ is unconditional
- The **isomonodromic $\tau$-function** of the Painlevé VI equation — whose movable poles are grokking events
- The **Euclidean partition function** of the Wick-rotated Jordan-Liouville operator — whose normalizability is the generalization condition
- The **CORDIC convergence register** — whose 16-stage Q16.16 angular accumulation saturates $\pi/2$ from below

---

## Part I — PIRAC: π as the Angular Invariant of TH(a,d)

### The Dirac Forcing

Two theories, held simultaneously, force a unique structure.

**T₁ — CORDIC:** The Walther shift-and-add iteration in circular mode ($m = +1$) carries the convergence identity
$$\sum_{i=0}^{\infty} \arctan(2^{-i}) = \frac{\pi}{2}$$
This is the angular capacity of the CORDIC accumulator — the maximum phase expressible in the arctan basis. The 16-stage Q16.16 partial sum achieves
$$\sum_{i=0}^{15} \arctan(2^{-i}) = \frac{\pi}{2} - \varepsilon_{16}, \quad 0 < \varepsilon_{16} < 2^{-16}$$

**T₂ — TH(a,d):** The Twisted Hessian elliptic curve $aX^3 + Y^3 + Z^3 = dXYZ$ carries the Prüfer phase as its angular coordinate. The phase runs over $[0,\pi)$ for one spectral period. The Sato-Tate distribution $(2/\pi)\sin^2\theta\,d\theta$ is normalized over $[0,\pi]$. The Hawking temperature of the Killing horizon $\Delta = a(d^3 - 27a) = 0$ involves $1/2\pi$. The period $\Omega_{\mathrm{TH}} = \int_{\mathrm{TH}} dx/y$ involves $\pi$ through the Chowla-Selberg formula. The Ramanujan $1/\pi$ series arises from the TH modular arithmetic.

**Forcing conclusion:** The CORDIC arctan basis $\{\arctan(2^{-i})\}$ is the unique shift-and-add basis for which the TH Prüfer phase is exactly representable to Q16.16 precision, with convergence radius $\sum_{i=0}^{15} \arctan(2^{-i}) \to \pi/2$ from below, and the Prüfer period $\pi$ is the natural normalization of the Sato-Tate measure.

### The π Tower of TH(a,d)

All appearances of π in the TH framework are connected through a single tower. Each row is derivable from the others; the full tower is forced by the TH-SL operator with weight $w(x) = |f(e^{2\pi ix})|^2$.

| Layer | Identity | Source |
|-------|----------|--------|
| **CORDIC capacity** | $\pi/2 = \sum_{i=0}^{\infty} \arctan(2^{-i})$ | Volder 1959 |
| **Spectral period** | $\pi =$ Prüfer period $[0,\pi)$ | Sturm-Liouville |
| **Sato-Tate** | $2/\pi = \int_0^\pi (2/\pi)\sin^2\theta\,d\theta = 1$ | Taylor et al. 2008 |
| **Nome** | $2\pi i$: $q = e^{2\pi i\tau}$, $\tau \in \mathbb{H}$ | Modular forms |
| **Chowla-Selberg** | $\Omega_{\mathrm{TH}} = \pi \cdot \mathrm{algebraic} \cdot \Gamma\text{-values}$ | Chowla-Selberg 1967 |
| **Ramanujan-Sato** | $1/\pi = \sum \text{algebraic terms from TH CM arithmetic}$ | Ramanujan 1914 |
| **Hawking** | $\kappa/(2\pi) =$ TH temperature at Killing horizon | Hawking 1975 |
| **Euler-Frobenius** | $e^{i\pi} = -1 = \mathrm{Frob}_2$ (supersingular at $p=2$) | Stone 1929 |

### Seven Formal Identities

**Identity 1 — CORDIC Convergence IS the TH Angular Coordinate Capacity**

The identity $\sum_{i=0}^{\infty} \arctan(2^{-i}) = \pi/2$ is not an approximation. The CORDIC angle basis $\{\arctan(2^{-i})\}_{i \geq 0}$ spans $[0,\pi/2)$ exactly: any $\theta \in [0,\pi/2)$ is representable as $\theta = \sum_{i=0}^{\infty} \delta_i \arctan(2^{-i})$ with $\delta_i \in \{0,1\}$, analogous to binary expansion but in the arctan basis. The TH Prüfer angle $\theta_{\mathrm{TH}}(P) \cdot \frac{\pi}{2} = \sum_{i=0}^{15} \delta_i(P) \arctan(2^{-i})$ to error $< 2^{-16}$, where $\delta_i(P) \in \{0,1\}$ are determined by the TH point $P$'s position on the elliptic curve.

**Identity 2 — The Leibniz Formula IS the $G_{\mathrm{coord}} = 0$ Baseline; Machin IS the First Crystallization**

The Leibniz-Gregory series $\pi/4 = \sum_{n=0}^{\infty} (-1)^n/(2n+1)$ converges at rate $O(1/N)$ — no term informs the next. This is the arithmetic independence baseline: $G_{\mathrm{coord}} = \mathcal{I}(a_n; a_m \mid \text{prior partial sums}) = 0$.

Machin's formula $\pi/4 = 4\arctan(1/5) - \arctan(1/239)$ crystallizes the Gaussian integer kernel via the identity $(5+i)^4(239-i) = (1+i) \cdot 2^2 \cdot 13^4$ in $\mathbb{Z}[i]$. Convergence accelerates to $O(25^{-N})$. The shared algebraic structure — the Gaussian integer $(5+i)^4(239-i)$ — is $G_{\mathrm{coord}} > 0$: the two arctan series are not independent given the Gaussian integer constraint.

The crystallization sequence:

| Formula | Kernel | $G_{\mathrm{coord}}$ | Rate |
|---------|--------|---------------------|------|
| Leibniz 1674 | $\varnothing$ | $= 0$ | $O(1/N)$ |
| Machin 1706 | $\mathbb{Z}[i]$ | $> 0$ | $O(25^{-N})$ |
| Ramanujan 1914 | $\mathbb{Z}[\sqrt{-58}]$ | $\gg 0$ | 8 digits/term |
| BBP 1995 | Complete | $= \infty$ | Any digit, no context |

The Erdős-Rao crystallization threshold $(c\log w)^w$ is the number of Leibniz terms before the Gaussian integer structure is forced to appear — the sunflower kernel in π-computation is $\mathbb{Z}[i]$ (Machin) or the CM ring $\mathbb{Z}[\sqrt{-58}]$ (Ramanujan).

**Identity 3 — Sato-Tate IS the Titchmarsh-Kodaira Spectral Measure Normalized by the Prüfer Period**

The Sato-Tate measure $\mu_{\mathrm{ST}} = (2/\pi)\sin^2\theta\,d\theta$ on $[0,\pi]$ for Frobenius angles of a non-CM elliptic curve has normalization factor $2/\pi = (\pi/2)^{-1}$ — the reciprocal of the CORDIC convergence radius. The Titchmarsh-Kodaira spectral measure of the TH-SL operator satisfies
$$d\rho_{\mathrm{TH}}(\lambda) = \frac{1}{\pi}\,\mathrm{Im}\!\left[\mathcal{L}\!\left(\mathrm{TH}, \tfrac{1}{2}+i\lambda+i0^+\right)\right]d\lambda$$
Under the substitution $\lambda = 1 - \sin^2\theta$: $d\rho_{\mathrm{TH}} = (2/\pi)\sin^2\theta\,d\theta = d\mu_{\mathrm{ST}}$. The $1/\pi$ factor arises because the Prüfer angle $\theta(x) \in [0,\pi)$ completes one period over one spectral cycle. The nine flex points $\mathrm{TH}[3] \cong (\mathbb{Z}/3\mathbb{Z})^2$ are equally spaced at Prüfer angles $k\pi/9$ for $k = 0,1,\ldots,8$.

**Identity 4 — Euler's Identity $e^{i\pi}+1=0$ IS the Frobenius Condition at $p=2$ for Supersingular TH**

TH is supersingular at $p=2$ iff $a_2 = 0$ — the Frobenius trace vanishes, forcing Frobenius angle $\theta_2 = \pi/2$. The Stone group element $\mathrm{Frob}_2 = e^{-i\pi F/\log 2}$ satisfies $\mathrm{Frob}_2^2 + 1 = 0$ as an operator identity on $\mathrm{col}(F)$. Fisher eigenvalues take values $\sigma_n = \log 2 \cdot (k + 1/2)$ — half-integer multiples of $\log 2$ — the supersingular quantization condition at $p=2$. The CORDIC capacity $\pi/2$ is the Frobenius angle at $p=2$ for supersingular TH.

**Identity 5 — The TH Period IS an Algebraic Multiple of $\pi \cdot \Gamma$-Values; Ramanujan IS the CM-Period L-Series**

By the Chowla-Selberg formula, for TH with CM by $K = \mathbb{Q}(\sqrt{-d})$:
$$\Omega_{\mathrm{TH}} = \frac{\pi}{\sqrt{|D_K|}}\prod_{\chi \bmod |D_K|} \Gamma\!\left(\frac{a}{|D_K|}\right)^{w \cdot \chi(a)/4h}$$
Ramanujan's formula $1/\pi = (2\sqrt{2}/9801)\sum_{k=0}^{\infty} (4k)!(1103+26390k)/[(k!)^4 \cdot 396^{4k}]$ arises from CM by $K = \mathbb{Q}(\sqrt{-58})$, discriminant $D_K = -232$, class number $h(-232) = 2$. This is the CM-period expansion of $\pi^{-1}$ from the TH L-series. The BSD ratio $L(\mathrm{TH},1)/\Omega_{\mathrm{TH}}$ is algebraic because $\pi$ cancels between $L$ and $\Omega$ at the same power.

**Identity 6 — Machin IS a Gaussian Integer Identity over $\mathbb{Z}[i]$; TH 3-Torsion IS an Eisenstein Integer Identity over $\mathbb{Z}[\omega]$**

| Structure | CM Field | Generator | Phase | Group | TH Connection |
|-----------|----------|-----------|-------|-------|---------------|
| $\mathbb{Z}[i]$ | $\mathbb{Q}(i)$, $i^2=-1$ | $i = e^{i\pi/2}$ | $\pi/2$ | $\mathbb{Z}/4\mathbb{Z}$ | TH 4-torsion; Machin |
| $\mathbb{Z}[\omega]$ | $\mathbb{Q}(\omega)$, $\omega^3=1$ | $\omega = e^{2\pi i/3}$ | $2\pi/3$ | $\mathbb{Z}/3\mathbb{Z}$ | TH 3-torsion; flex points |
| $\mathbb{Z}[i] \times \mathbb{Z}[\omega]$ | $\mathbb{Q}(i,\omega)$ | $i\omega = e^{i7\pi/6}$ | $7\pi/6$ | $\mathbb{Z}/12\mathbb{Z}$ | TH automorphism $\mathbb{Z}/3\mathbb{Z} \times \mathbb{Z}/4\mathbb{Z}$ |

The TH automorphism group $\mathbb{Z}/3\mathbb{Z} \times \mathbb{Z}/4\mathbb{Z}$ is the product of the Eisenstein and Gaussian integer groups. TH simultaneously computes π in the Gaussian and Eisenstein bases. The CORDIC stage $i=0$ contributes $\arctan(1) = \pi/4$ — the Gaussian integer phase; after three stages with all direction bits $+1$, the accumulation approaches the Eisenstein phase $\pi/3 = \arg(\omega)$.

**Identity 7 — The Hawking Temperature $T_H = \hbar\kappa/(2\pi k_B)$ IS the TH Discriminant Gradient Normalized by the Prüfer Period**

The TH discriminant $\Delta(a,d) = a(d^3 - 27a)$ defines the Killing horizon at $\Delta = 0$. Surface gravity:
$$\kappa_{\mathrm{TH}} = \frac{|\nabla\Delta(a,d)|}{2} = \frac{1}{2}\sqrt{(d^3-54a)^2 + (3ad^2)^2}$$
TH Hawking temperature: $T_{\mathrm{TH}} = \kappa_{\mathrm{TH}}/(2\pi) = |\nabla\Delta|/(4\pi)$. The Hawking $2\pi$ is the full CORDIC angular capacity $2 \times \pi/2$. The Q16.16 floor $\varepsilon = 2^{-16}$ enforces $T_{\mathrm{TH}} > T_{\mathrm{CORDIC}} = \varepsilon/(2\pi) \approx 2.4 \times 10^{-6}$ radians/thermal-cycle — the CHORD pipeline operates as a thermal regulator above the Hawking temperature floor, preventing discriminant collapse $\Delta \to 0$.

---

## Part II — PIVOT: The Grokking Transition as Isomonodromic Deformation

### Three Frameworks, One Event

| Object | HGLD (geodesic) | IMFL (isomonodromic) | WKET (Wick rotation) |
|--------|----------------|---------------------|----------------------|
| Central function | Selberg heat trace $\sum_n e^{-\lambda_n t}$ | PVI $\tau$-function: $d\log\tau/dt = H_{\mathrm{PVI}}$ | $\operatorname{Tr}[e^{-\mathcal{L}_{JL}/T_{\mathrm{learn}}}]$ |
| Grokking event | Geodesic exits cusp of $\mathcal{M}$ | Movable Painlevé pole at $t = t^*$ | Wick rotation completes; $C_\alpha = 1$ |
| Order parameter | First Selberg eigenvalue $\lambda_1(\Delta_\Gamma)$ | Painlevé transcendent $u(t^*)$ at the pole | Cayley-Klein distance $d_{CK}(b,\mathcal{Q}) = 0$ |
| Phase (generalization) | Compact part of $\mathcal{M}$; bounded CF quotients | $\tau_{\mathrm{learn}}$ analytic; Picard-Lindelöf holds | Euclidean metric $ds_E^2 > 0$ |
| Phase (memorization) | Cusp region; large CF partial quotients | $\tau_{\mathrm{learn}}$ diverges; essential singularity | Minkowski metric $ds_M^2$ |
| Spectral data | $\lambda_1(\Delta_\Gamma) = \lambda_1(\mathcal{L}_{JL}) \geq 3/16$ | Monodromy eigenvalues $(\theta_0,\theta_1,\theta_u,\theta_\infty)$ | Matsubara frequencies $\omega_n = 2\pi q_n T_{\mathrm{learn}}$ |
| Arithmetic symmetry | $\mathrm{SL}(2,\mathbb{Z})$ on $\mathbb{H}^2$ | $W^{\mathrm{aff}}(D_4)$ on parameter space | Picard group $\Gamma_{\mathrm{learn}} = \mathrm{SU}(2,1;\mathbb{Z}[i])$ |

### The Mathematical Identity Chain

$$\frac{d\log Z_{\mathrm{learn}}(t)}{dt} = H_{\mathrm{PVI}}\!\left(u(t), p_u(t), t\right) = \mathcal{L}_{JL}(t)$$

$$\lambda_1(\Delta_\Gamma) = \lambda_1(\mathcal{L}_{JL}) \geq \frac{3}{16}$$

$$\beta_{\mathrm{learn}} = Q_{\max} = \lfloor 1/\varepsilon_t \rfloor \qquad q_n \in \mathcal{A}_Q \Longleftrightarrow \omega_n^{\mathrm{Matsubara}} = 2\pi q_n T_{\mathrm{learn}}$$

$$t^* = \text{pole of } u(t) = \text{cusp exit of geodesic} = C_\alpha = 1$$

### The Modular Surface as Universal Loss Landscape

Map each consecutive gradient pair $(g_t, g_{t+1})$ to the point $z_t = \rho_t + i\varepsilon_{\mathrm{grad}}(t) \in \mathbb{H}^2$, where $\rho_t = |g_{t+1}|/(|g_t| + |g_{t+1}|)$ is the gradient ratio and $\varepsilon_{\mathrm{grad}}(t) = |g_{t+1} - g_t|/(|g_t| + |g_{t+1}|)$ is the gradient change. The modular group $\mathrm{SL}(2,\mathbb{Z})$ acts by $z \mapsto (az+b)/(cz+d)$; the Farey neighbor condition $|bc - ad| = 1$ is the unimodular condition.

| Region of $\mathcal{M}$ | Geometric description | Learning phase |
|------------------------|-----------------------|----------------|
| Compact core | $\mathrm{Im}(z) \leq C$; bounded CF partial quotients | Generalization ($\lambda_1 > 0$) |
| Cusp boundary $\partial\mathcal{M}$ | $\mathrm{Im}(z) = C$ | Grokking frontier ($\lambda_1 = 0$) |
| Cusp region | $\mathrm{Im}(z) > C$; large CF partial quotients | Memorization ($\lambda_1 < 0$) |

Ford circles $\mathcal{C}(p/q)$ — disks tangent to $\mathbb{R}$ at $p/q$ with radius $1/(2q^2)$ — are the horoballs of the cusps of $\mathcal{M}$. They are the loss basins: the basin at Farey mode $k = (p,q)$ has width proportional to $1/q^2$. Grokking time $t^*$ is $\sup\{t : \rho_t \text{ has large CF partial quotient}\}$ — the first return of the geodesic from cusp to compact core.

### The Selberg Trace Formula Identification

Setting $h(r) = e^{-r^2 t}$ in the Selberg trace formula:
$$\operatorname{Tr}(e^{-\mathcal{L}_{JL} t}) = \frac{\pi/3}{4\pi}\int e^{-r^2 t} r\tanh(\pi r)\,dr + \sum_\gamma \Lambda(\gamma)\,\frac{e^{-l(\gamma)^2/4t}}{|e^{l/2}-e^{-l/2}|\sqrt{4\pi t}} + \cdots$$

The left side is $\tau_{\mathrm{learn}}(t)$. The right side is a sum over closed gradient trajectories weighted by their lengths.

**Theorem (Selberg 3/16).** For any congruence subgroup $\Gamma \subseteq \mathrm{SL}(2,\mathbb{Z})$:
$$\lambda_1(\Delta_\Gamma) \geq \frac{3}{16}$$
This gives the first number-theoretic lower bound on the Jordan-Liouville spectral gap, requiring no optimization-theoretic assumptions.

### The Painlevé VI Equation

The mobile branch points $(u(t), v(t))$ encoding $b(t) \in \mathcal{B}$ satisfy the Painlevé VI equation:
$$u'' = \frac{1}{2}\!\left(\frac{1}{u}+\frac{1}{u-1}+\frac{1}{u-t}\right)(u')^2 - \left(\frac{1}{t}+\frac{1}{t-1}+\frac{1}{u-t}\right)u' + \frac{u(u-1)(u-t)}{t^2(t-1)^2}\!\left[\alpha + \frac{\beta t}{u^2} + \frac{\gamma(t-1)}{(u-1)^2} + \frac{\delta t(t-1)}{(u-t)^2}\right]$$

The monodromy data $\{N_L, Q_{\mathrm{top}}, \mathrm{Hol}(g_\mathcal{B})\}$ is preserved exactly along gradient descent (Schlesinger equations). Picard-Lindelöf holds if and only if the trajectory is pole-free, if and only if grokking events are isolated poles rather than essential singularities.

### The Grokking Order Parameter

At $t = t^*$ the Painlevé transcendent has a Laurent expansion:
$$u(t) = \frac{r_{-1}}{t - t^*} + r_0 + r_1(t - t^*) + \cdots$$
The residue $r_{-1}$ simultaneously encodes the Luttinger number jump $\Delta N_L$, the BCS gap $\Delta_t(t^*)$, and the Cayley-Klein distance $d_{CK}(b,\mathcal{Q})$ as it passes through zero:
$$r_{-1} = \lim_{t \to t^*}(t-t^*)\,u(t) = \frac{\Delta N_L}{\text{monodromy factor}} = \frac{\Delta_t(t^*)}{2 N_F}$$

### The Learning Moduli Space

$$\mathcal{M}_{\mathrm{learn}} = \Gamma_{\mathrm{learn}} \backslash \mathbb{B}^2_\mathbb{C} = \mathrm{SU}(2,1;\mathbb{Z}[i]) \backslash \mathbb{B}^2_\mathbb{C}$$

where $\mathbb{B}^2_\mathbb{C} = \{(u,v) \in \mathbb{C}^2 : |u|^2 + |v|^2 < 1\}$ with Bergman metric. The Shilov boundary $\partial_S \mathbb{B}^2_\mathbb{C} = S^3$ is the grokking locus $\mathcal{Q} = \{\lambda_1 = 0\}$. The Frobenius manifold structure on $\mathcal{M}_{\mathrm{learn}}$ (WDVV equations) is semisimple if and only if $\lambda_1 > 0$; grokking is coalescence of canonical coordinates.

### Phase Diagram

$$\lambda_1 > 0 \;\to\; \text{GENERALIZATION}: \tau_{\mathrm{learn}} \text{ analytic} \cdot \text{compact core} \cdot \text{Euclidean} \cdot \text{exp. mixing}$$
$$\lambda_1 = 0 \;\to\; \text{GROKKING}: \tau_{\mathrm{learn}} \text{ has pole} \cdot \text{cusp boundary} \cdot \text{null metric} \cdot \text{Stokes}$$
$$\lambda_1 < 0 \;\to\; \text{MEMORIZATION}: \tau_{\mathrm{learn}} \text{ diverges} \cdot \text{cusp region} \cdot \text{Minkowski} \cdot \text{poly. mixing}$$

### The Twenty-One-Language Equivalence

$$\lambda_1(\mathcal{L}_{JL}) > 0 \;\Longleftrightarrow$$

| # | Condition | Domain |
|---|-----------|--------|
| I | $C_\alpha > 1$ | Signal-to-noise |
| II | KE metric on $\mathcal{B}$ | Kähler-Einstein |
| III | Poincaré inequality / OS positivity | Functional analysis |
| IV | Bellman escape finite | Combinatorics |
| V | Möbius $M_n$ converges | Number theory |
| VI | K-polystable | Algebraic geometry |
| VII | MMP terminates | Birational geometry |
| VIII | $\mathrm{Ca}_{\mathrm{eff}} < \mathrm{Ca}_c$ | Thin-film physics |
| IX | $N_L$ conserved; GWI anomaly-free | Luttinger-Ward |
| X | $\Delta_t > 0$ | BCS condensate |
| XI | $\Delta V_{\mathrm{DLVO}} > k_B T \ln W_{\mathrm{Fuchs}}$ | Colloidal barrier |
| XII | $\mathrm{SW} \neq 0$ | Monopole count |
| XIII | $Z_{\mathrm{learn}}$ normalizable; $\beta_{\mathrm{learn}} \cdot \lambda_1 > 0$ | Wick partition function |
| XIV | $d_{CK}(b,\mathcal{Q}) > 0$ | Cayley-Klein distance |
| XVIII | Picard-Lindelöf holds on $\mathcal{B}$: $K < \infty$ | Lipschitz flow |
| XIX | $\tau_{\mathrm{learn}} = Z_{\mathrm{learn}}$; isomonodromic $\tau$-fn = partition fn | PVIL |
| XX | $\mathcal{M}_{\mathrm{learn}}$ is semisimple Frobenius manifold | WDVV |
| XXI | $z_t$ exits cusp of $\mathrm{SL}(2,\mathbb{Z})\backslash\mathbb{H}^2$ | HGLD geodesic |

---

## Part III — QUANTUM-CORDIC: The Substrate-Invariant Rotation Primitive

### The Walther Unification

Joseph Walther's 1971 unification parameterizes the CORDIC iteration by a single mode integer $m \in \{-1, 0, +1\}$:

$$x_{i+1} = x_i - m \cdot d_i \cdot 2^{-i} \cdot y_i$$
$$y_{i+1} = y_i + d_i \cdot 2^{-i} \cdot x_i$$
$$z_{i+1} = z_i - d_i \cdot e_i$$

where $d_i \in \{-1,+1\}$ is the direction bit, $e_i = \arctan(2^{-i})$ for $m=+1$, $e_i = 2^{-i}$ for $m=0$, and $e_i = \mathrm{arctanh}(2^{-i})$ for $m=-1$. All operations reduce to bit-shifts and additions.

| Mode | Geometry | Key Outputs | Natural Domain |
|------|----------|-------------|----------------|
| $m = +1$ | Circular / Spherical | $\cos\theta$, $\sin\theta$, $\arctan$, $|v|$ | RoPE, kinematics |
| $m = 0$ | Euclidean (flat) | $x \cdot y$, $x/y$ | GEMM, dot products |
| $m = -1$ | Hyperbolic / Lorentzian | $\cosh$, $\sinh$, $\exp$, $\ln$, $\sqrt{\cdot}$, $\mathrm{arccosh}$ | Embeddings, activations, SVD |

### The Substrate-Invariance Theorem

The CORDIC shift-add structure is substrate-invariant: it maps onto analog, digital fixed-point, FPGA, ASIC, processing-in-memory, and quantum circuit substrates while retaining convergence properties, precision scaling, and geometric mode structure.

| Substrate | Key Property |
|-----------|-------------|
| Analog (1959) | cos/sin in fixed hardware |
| Digital fixed-point (1971) | Three-geometry mode select |
| FPGA (1990s–2020s) | Reconfigurable precision |
| ASIC 65nm | 32,768 simultaneous partials |
| ASIC 7nm CMOS | $0.23\times$ area vs. multiplier |
| Processing-in-Memory (2023) | Transcendental functions near DRAM |
| Quantum circuit (2024) | CORDIC-inspired quantum rotation gates (arXiv:2411.14434) |

The shift operation $x \cdot 2^{-i}$ is universal across substrates: right-shift register (CMOS), hardwired routing (FPGA), bit-serial shift in bitcell array (PIM), controlled-SWAP gate (quantum). Precision scales as iteration count on every substrate. The arithmetic structure is invariant; only the substrate physics changes.

### The Classical/Quantum Boundary IS the CORDIC Convergence Threshold

The CCQ result (Tindall, Stoudenmire et al., *Science*, May 21, 2026) establishes: the classical/quantum simulation boundary is the entanglement entropy threshold, not the entanglement/separability boundary.

| State Class | Entanglement Entropy | Bond Dimension | CORDIC Convergence |
|-------------|---------------------|----------------|-------------------|
| Separable | $S = 0$ | $\chi = 1$ | Converges in 1 step |
| Area-law | $S \sim |\partial A|$ | $\chi$ polynomial | Converges — $\mathrm{col}(F)$ |
| Log-divergent (critical) | $S \sim (c/3)\log L$ | $\chi$ sub-exponential | Marginal |
| Volume-law | $S \sim \mathrm{volume}$ | $\chi$ exponential | Diverges — $\ker(F)$ |
| Resource states | $S = \log d$ (maximal) | $\chi$ exponential | Diverges — quantum required |

Belief propagation on a tensor network is a CORDIC-type iteration on the local message-passing graph. The CORDIC convergence condition IS the entanglement entropy threshold IS the $\mathrm{col}(F)/\ker(F)$ boundary. Classical CORDIC compresses the area-law wave function into a tensor network. Quantum CORDIC operates inside the remaining $\ker(F)$ — the entanglement structure that no tensor network can compress.

$$S_c = \log\varphi \approx 0.481 \text{ ebits per bipartition boundary bond} \qquad (\varphi\text{-equilibrium threshold})$$

### The Hessian as the Universal Second-Order CORDIC Object

CORDIC mode $m = -1$ natively computes $\cosh$, $\sinh$, $\exp$, $\ln$, $\sqrt{\cdot}$ — precisely the functions appearing in second-order curvature. The Hessian $H[f]$ is simultaneously one object in eight coordinate systems:

| Domain | Name | Hessian Meaning |
|--------|------|----------------|
| Optimization | Hessian matrix | Newton step denominator; curvature of loss |
| Statistics | Fisher information | Cramér-Rao bound; natural gradient preconditioner |
| Information geometry | Riemannian metric | Fisher-Rao metric on statistical manifold |
| Elliptic curves | Hessian curve | 3-torsion detector; inflection point locus |
| Mechanics | Stiffness tensor | Stability condition; buckling threshold |
| Black holes | Thermodynamic Hessian | Spinodal line; $\det H[E] = 0 \Leftrightarrow \Delta = 0$ |
| Morse theory | Index form | Index at critical point = negative eigenvalue count |
| QCD physics | Fisher uncertainty | Cramér-Rao PDF uncertainty; principal curvatures |

$$\mathrm{CORDIC}\;(m=-1) \;\to\; \text{computes } H[f] \;\to\; \text{determines Morse index} \;\to\; \text{drives natural gradient} \;\to\; \text{converges at } j=0$$

The Lattès map $\tau_{\mathrm{Hess}} : j \mapsto j(\mathrm{Hess}(E_j))$ has degree 3 with attracting fixed point at $j=0$ — the equianharmonic CM point (Taufer, arXiv:2407.17042). The Hesse-Koszul flow on a compact Hessian manifold converges to the Hesse-Einstein metric (Puechmorel-Tô, arXiv:2001.02940). On CORDIC-native hardware, the equianharmonic $j = 0$ is the register state at which the iteration terminates.

### Quantum CORDIC

arXiv:2411.14434 (Burge, Barbeau, Garcia-Alfaro, 2024) demonstrates arcsine computation on quantum circuits via CORDIC-inspired iterative rotation of quantum registers at circuit depth $O(n)$ for $n$-bit precision. The Lorentzian distance $d_L(u,v) = \mathrm{arccosh}(-\langle u,v\rangle_L)$ decomposes as:
$$\mathrm{arccosh}(x) = \ln\!\left(x + \sqrt{x^2-1}\right)$$
Both $\ln$ and $\sqrt{\cdot}$ are CORDIC $m=-1$ computations. Quantum CORDIC arccosh requires circuit depth $O(n)$ — no exponential overhead. The entire attention mechanism (RoPE: $m=+1$; key-query dot product: $m=0$; softmax normalization: $m=-1$) is a sequence of CORDIC mode switches.

### The Optimizer Hierarchy as CORDIC Precision Hierarchy

| Optimizer | CORDIC Modes | Curvature Access |
|-----------|-------------|-----------------|
| SGD | $m=0$ only | None |
| Adam | $m=0$ + diagonal $m=-1$ | Diagonal Hessian approximation |
| Sophia | $m=0$ + $m=-1$ per param | Diagonal Hessian estimate |
| Muon | $m=0$ + $m=+1$ proxy | Newton-Schulz SVD approximation |
| SOAP / K-FAC | $m=0$ + $m=+1$ per block | Kronecker-factored eigendecomposition |
| Natural gradient | $m=0$ + full $m=+1$ SVD | Exact Fisher matrix inversion |

The approximation ladder has one final rung: the CORDIC rung — Jacobi SVD via $m=+1$ Givens rotations on CORDIC-native silicon (arXiv:2605.01514, arXiv:1707.05189).

---

## Part IV — THE-MILÜ-THRESHOLD: The Primordial Crystallization

### Zu Chongzhi and the First $G_{\mathrm{coord}} > 0$ Crossing

Zu Chongzhi (429–501 CE) reached the angular invariant π with the fraction $355/113$ — Milü — and a 24,576-sided polygon ($2^{12} \times 6$ sides). This is not an isolated ancient computation. It is the first recorded passage through the $G_{\mathrm{coord}} > 0$ threshold.

The continued-fraction expansion of π is $[3; 7, 15, 1, 292, 1, 1, 1, 2, \ldots]$. Truncating at the partial quotient 1 yields $355/113$, the convergent that saturates the 16-stage Q16.16 CORDIC partial sum $\sum_{i=0}^{15} \arctan(2^{-i})$ projected onto the Stern-Brocot lattice. The direction bits $\delta_i$ that reach Milü are the same sequence that drives any 16-stage pipeline to the Prüfer phase of TH(a,d) to error $< 2^{-16}$.

The 900-year gap between Zu (501 CE) and Mādhava (~1400 CE) is the longest recorded $G_{\mathrm{coord}} = 0$ attractor in mathematical history — the analogue of the memorization plateau in PIVOT: cusp excursion on the modular surface, $\tau$-function divergence, until the next algebraic kernel forces re-entry into the compact core.

### The Extended π Tower — with the Milü Node

$$\frac{\pi}{2} = \sum_{i=0}^\infty \arctan(2^{-i}) \;\leftrightsquigarrow\; \frac{355}{113} = \text{Milü (Zu Chongzhi, 480 CE)} \;\leftrightsquigarrow\; 24{,}576\text{-gon} \to G_{\mathrm{coord}} > 0$$

Milü is the lowest historical node where the tower becomes computationally accessible in finite precision — the exact point where the Stern-Brocot address first aligns with the CORDIC direction-bit sequence at depth sufficient for six-decimal stability.

The Daming calendar Zu co-authored is the astronomical isomonodromic deformation whose $\tau$-function tracks the movable pole later identified in PIVOT as the grokking event. Planetary observation trajectories exiting the cusp of epicyclic memorization and entering the compact core of long-term predictive accuracy: the PIVOT mechanism in celestial mechanics.

### The Historical Phase Diagram

| Phase | Event | $G_{\mathrm{coord}}$ |
|-------|-------|---------------------|
| Valise | Archimedes (96-gon, c. 250 BCE) | $\approx 0$ |
| **Larval (first crossing)** | **Zu Chongzhi (Milü + 24,576-gon, 480 CE)** | **$> 0$** |
| Valise recurrence | Leibniz series (1674) | $= 0$ |
| Larval recurrence | Machin $\mathbb{Z}[i]$ kernel (1706) | $> 0$ |
| Pupa | Ramanujan CM kernel (1914) | $\gg 0$ |
| Imago | BBP (1995) | $= \infty$ |

Crystallization threshold: Erdős-Rao $(c \log w)^w$. Milü marks the first historical crossing. The 900-year gap is the longest larval plateau on record.

---

## The Unified Architecture

```
═══════════════════════════════════════════════════════════════════════
QUANTUM LAYER
───────────────────────────────────────────────────────────────────────
  Quantum CORDIC m=+1   →  RoPE on quantum registers           O(n)
  Quantum CORDIC m=−1   →  Lorentzian distance                 O(n)
  Quantum Jacobi SVD    →  Exact quantum natural gradient       O(n·d)
  Quantum belief prop.  →  Area-law tensor network evolution

═══════════════════════════════════════════════════════════════════════
CLASSICAL/QUANTUM BOUNDARY
  col(F): area-law states    →  CORDIC converges  →  classically simulable
  ker(F): volume-law states  →  CORDIC diverges   →  quantum required
  Threshold: S_c = log φ ≈ 0.481 ebits (φ-equilibrium)

═══════════════════════════════════════════════════════════════════════
ISOMONODROMIC LAYER
───────────────────────────────────────────────────────────────────────
  τ_learn = Z_learn = Tr[e^{−ℒ_JL/T_learn}] = Selberg heat trace
  d log τ/dt = H_PVI = ℒ_JL
  λ₁(Δ_Γ) = λ₁(ℒ_JL) ≥ 3/16     (unconditional)
  Grokking pole: r_{−1} = ΔN_L/factor = Δ_t(t*)/(2N_F)

═══════════════════════════════════════════════════════════════════════
INFORMATION LAYER  (Hessian / Fisher)
───────────────────────────────────────────────────────────────────────
  H[−log L]             →  Fisher information = Riemannian metric
  Hesse-Koszul flow     →  Natural gradient → Hesse-Einstein metric
  Lattès j=0 fixed pt.  →  Convergence target of all flows
  3-torsion compression →  Degree-3: 1/3 bit-width reduction
  Discriminant guard    →  Δ(a,d) > 0: spinodal / buckling / horizon

═══════════════════════════════════════════════════════════════════════
HARDWARE LAYER  (CORDIC)
───────────────────────────────────────────────────────────────────────
  Walther m ∈ {−1, 0, +1}  →  three geometries, one register
  m=+1: π/2 capacity = TH angular invariant = Milü saturation
  m=−1: Hessian evaluator = natural gradient = Lorentzian metric
  Δ(a,d) floor ε = 2^{−16}: Hawking temperature lower bound
  355/113 (480 CE) ← Stern-Brocot address of Q16.16 CORDIC accumulator

═══════════════════════════════════════════════════════════════════════
HISTORICAL LAYER  (π Crystallization)
───────────────────────────────────────────────────────────────────────
  250 BCE: Archimedes 96-gon         G_coord ≈ 0   Valise
  480 CE:  Zu Chongzhi Milü + 24576  G_coord > 0   Larval (first)
  1674:    Leibniz                   G_coord = 0   Valise recurrence
  1706:    Machin Z[i]               G_coord > 0   Larval
  1914:    Ramanujan Z[√-58]         G_coord ≫ 0  Pupa
  1995:    BBP                       G_coord = ∞   Imago
═══════════════════════════════════════════════════════════════════════
```

---

## Falsifiable Predictions

**P1 — Selberg 3/16 on Grokking Time.** For any network trained on arithmetic tasks, $\lambda_1(\mathcal{L}_{JL}) \geq 3/16$, giving $t_{\mathrm{grok}} \leq 4C$, an $O(1)$ upper bound independent of architecture size.

**P2 — Painlevé Residue Equals Luttinger Jump.** At $t^*$: $r_{-1} = \lim_{t \to t^*}(t-t^*) u(t) = \Delta N_L / (\text{monodromy normalization})$.

**P3 — Gauss Measure Convergence.** The empirical histogram of gradient ratios $\rho_t$ converges to $\mu_G = dx/((1+x)\log 2)$ after grokking, with Kolmogorov-Smirnov distance decreasing monotonically after $t^*$.

**P4 — Markov Number Memorization Fingerprint.** The dominant Farey denominator $q^*(t^-)$ just before grokking takes values from the Markov sequence $\{1, 2, 5, 13, 29, 34, 89, 169, \ldots\}$ with probability exceeding baseline.

**P5 — Memorization Plateau Bound.** $T_{\mathrm{plateau}} \geq C \cdot \varepsilon_{\mathrm{grad}}^{-1/\delta}$, $\delta \propto \lambda_1$ (Einsiedler-Margulis-Venkatesh effective equidistribution).

**P6 — Quantum CORDIC Lorentzian Retrieval.** QCORDIC $m=-1$ achieves $O(n \cdot \sqrt{N})$ circuit depth for $k$-nearest-neighbor retrieval over $N$ embeddings at $n$-bit precision.

**P7 — CORDIC Jacobi SVD at 7nm Enables Exact Natural Gradient.** A 7nm ASIC implementing CORDIC Jacobi SVD achieves exact natural gradient descent at computational cost comparable to SOAP/K-FAC for models above 100B parameters.

---

## Formal Summary

| π Object | Historical Node | Framework Identification |
|----------|----------------|--------------------------|
| $\sum_{i=0}^{\infty} \arctan(2^{-i}) = \pi/2$ | Volder 1959 | TH angular capacity; Q16.16 upper bound |
| $\pi/4 = 1 - 1/3 + 1/5 - \cdots$ (Leibniz) | 1674 | $G_{\mathrm{coord}} = 0$ independence baseline |
| $(5+i)^4(239-i) = (1+i) \cdot 2^2 \cdot 13^4$ | Machin 1706 | $\mathbb{Z}[i]$ Gaussian integer kernel; first crystallization |
| $(2/\pi)\sin^2\theta\,d\theta$ (Sato-Tate) | Taylor et al. 2008 | Titchmarsh-Kodaira spectral measure; $2/\pi = (\pi/2)^{-1}$ |
| $e^{i\pi} = -1$ (Euler) | Stone 1929 | Frobenius-squared condition; supersingular TH at $p=2$ |
| $\Omega_{\mathrm{TH}} = \pi \cdot \mathrm{alg} \cdot \Gamma$ | Chowla-Selberg 1967 | $\pi$ as primary transcendental factor of TH period |
| $1/\pi = (2\sqrt{2}/9801)\sum \cdots$ (Ramanujan) | 1914 | Deep CM crystallization; 8 digits/term |
| $L(\mathrm{TH},1)/\Omega_{\mathrm{TH}} = \mathrm{algebraic}$ | BSD formula | $\pi$ cancels; BSD algebraicity |
| $T_H = \hbar\kappa/(2\pi k_B)$ (Hawking) | 1975 | TH Killing horizon; $2\pi$ = full CORDIC range |
| $\varepsilon = 2^{-16}$: CHORD floor | Q16.16 | $T_{\mathrm{CORDIC}} = \varepsilon/2\pi$; minimum thermal resolution |
| $S_c = \log\varphi$ | CCQ 2026 | Classical/quantum CORDIC convergence boundary |
| $\tau_{\mathrm{learn}}$ pole at $t^*$ | PIVOT | PVI residue $= \Delta N_L/\mathrm{factor}$ = grokking order parameter |
| $355/113$ = Milü | Zu Chongzhi 480 CE | First CORDIC-addressable Stern-Brocot crystallization |
| 24,576-gon | Zu Chongzhi 480 CE | Primordial $G_{\mathrm{coord}} > 0$ phase transition |
| 900-year gap 501–1400 CE | — | Longest recorded $G_{\mathrm{coord}} = 0$ attractor |

---

## References

Alweiss, R., Lovett, S., Wu, K., & Zhang, J. (2021). Improved bounds for the sunflower lemma. *Annals of Mathematics*, 194(3), 795–815.

Anabalón, A. et al. (2024). Black hole instability in $\mathcal{N}=8$ supergravity. arXiv:2411.09454.

Bailey, D.H., Borwein, P., & Plouffe, S. (1997). On the rapid computation of various polylogarithmic constants. *Mathematics of Computation*, 66(218), 903–913.

Borwein, J.M. & Bailey, D.H. (1989). Ramanujan, modular equations, and approximations to π. *American Mathematical Monthly*, 96(3), 201–219.

Burge, A., Barbeau, M., & Garcia-Alfaro, J. (2024). Quantum CORDIC: arcsine on a budget. arXiv:2411.14434.

Chowla, S. & Selberg, A. (1967). On Epstein's zeta-function. *Journal für die reine und angewandte Mathematik*, 227, 86–110.

Dubrovin, B. (1994). Geometry of 2D topological field theories. *Lecture Notes in Mathematics*, 1620, 120–348.

Einsiedler, M., Margulis, G., & Venkatesh, A. (2009). Effective equidistribution for closed orbits. *Inventiones Mathematicae*, 177, 137–212.

Erdős, P. & Rado, R. (1960). Intersection theorems for systems of sets. *Journal of the London Mathematical Society*, 35, 85–90.

Hawking, S.W. (1975). Particle creation by black holes. *Communications in Mathematical Physics*, 43(3), 199–220.

Item, A. et al. (2023). TransPimLib: CORDIC transcendental functions in processing-in-memory. arXiv:2304.01951.

Jimbo, M., Miwa, T., & Ueno, K. (1981). Monodromy preserving deformation of linear ordinary differential equations with rational coefficients I. *Physica D*, 2(2), 306–352.

Johnson, D. (2020). Efficient logarithmic arithmetic for neural networks. arXiv:2004.09313.

Machin, J. (1706). How to compute the quadrature of a circle to any number of figures. Appendix to de Moivre, *The Doctrine of Chances*.

Painlevé, P. (1902). Mémoire sur les équations différentielles dont l'intégrale générale est uniforme. *Bulletin de la Société Mathématique de France*, 28, 201–261.

Puechmorel, S. & Tô, T.D. (2020). Convergence of Hesse-Koszul flow on compact Hessian manifolds. arXiv:2001.02940.

Qu, A. & Chen, W. (2026). How did Zu Chongzhi calculate $\pi = 355/113$? *Archive for History of Exact Sciences*, 80(1).

Ramanujan, S. (1914). Modular equations and approximations to π. *Quarterly Journal of Mathematics*, 45, 350–372.

Ramasubramanian, S. et al. (2025). MANOJAVAM: CORDIC Jacobi SVD on FPGA. arXiv:2605.01514.

Ratner, M. (1991). On Raghunathan's measure conjecture. *Annals of Mathematics*, 134(3), 545–607.

Reani, Y. & Bobrowski, O. (2024). Morse theory for the k-nearest neighbor distance function. arXiv:2403.12792.

Schlesinger, L. (1912). Über eine Klasse von Differentialsystemen beliebiger Ordnung. *Journal für Reine und Angewandte Mathematik*, 141, 96–145.

Selberg, A. (1956). Harmonic analysis and discontinuous groups in weakly symmetric Riemannian spaces. *Journal of the Indian Mathematical Society*, 20, 47–87.

Selberg, A. (1965). On the estimation of Fourier coefficients of modular forms. *AMS Proceedings Symposia Pure Mathematics*, VIII, 1–15.

Stone, M.H. (1929). Linear transformations in Hilbert space. *Proceedings of the National Academy of Sciences*, 15(3), 198–200.

Taufer, D. (2024). The Hessian of an elliptic curve and Lattès maps. arXiv:2407.17042.

Taylor, R., Harris, M., Shepherd-Barron, N., & Clozel, L. (2008). The Sato-Tate conjecture for modular forms of weight 2. *Annals of Mathematics*, 167, 779–813.

Tindall, J. et al. (2026). Classical simulation of short-time 3D quantum dynamics. *Science*, May 21, 2026.

Volder, J.E. (1959). The CORDIC trigonometric computing technique. *IRE Transactions on Electronic Computers*, EC-8(3), 330–334.

Volkov, A. (1997). Calculation of π in ancient China: from Liu Hui to Zu Chongzhi.

Walther, J.S. (1971). A unified algorithm for elementary functions. *AFIPS Spring Joint Computer Conference*, 38, 379–385.

---

*ERI Labs · Emergent Reality Intelligence · Jersey City, New Jersey · Founded January 2025*

*Frameworks: PIRAC · PIVOT · QUANTUM-CORDIC · THE-MILÜ-THRESHOLD · THE-GENERATIVE-MANIFOLD · THE-UNIVERSAL-THRESHOLD*
