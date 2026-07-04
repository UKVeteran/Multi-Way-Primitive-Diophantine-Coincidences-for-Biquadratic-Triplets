# Multi-Way Primitive Diophantine Coincidences for Biquadratic Triplets

> [!NOTE]
> **Paper Title:** Computational Investigation of Multi-Way Primitive Diophantine Coincidences for Biquadratic Triplets  
> **Author:** Johar M. Ashfaque  
> **Date:** July 3, 2026  
> **Primary Discovery:** Isolation of an exceptional 4-way primitive Diophantine collision for the sum of three fourth powers sharing the minimal invariant sum *S* = 5,978,882.

<hr>

## 1. The 1729 Connection: From Ramanujan to Biquadratic Hypersurfaces

To understand the core significance of this repository and Ashfaque's computational discoveries, one must first look at **1729**—the famous **Hardy-Ramanujan number**. Historically, 1729 is the smallest positive integer that can be expressed as the sum of two positive cubes in two distinct ways:

<p align="center">
<code>1<sup>3</sup> + 12<sup>3</sup> = 9<sup>3</sup> + 10<sup>3</sup> = 1729</code>
</p>

In number theory and Diophantine geometry, 1729 lies at the foundational heart of **Taxicab-type problems**. These problems seek integer solutions to equal sums of like powers, mathematically generalized as:

<p align="center">
<code>&Sigma;<sub><i>i</i>=1</sub><sup><i>m</i></sup> <i>x<sub>i</sub><sup>k</sup></i> = &Sigma;<sub><i>j</i>=1</sub><sup><i>m</i></sup> <i>y<sub>j</sub><sup>k</sup></i></code>
</p>

While classical Taxicab numbers (beginning with 1729) explore two-summand cubic equations (<i>m</i> = 2, <i>k</i> = 3) which have been extensively cataloged over the centuries, Ashfaque's work pushes this conceptual framework into a much less charted structural topology.

Specifically, this research investigates **three-summand biquadratic equations** (<i>m</i> = 3, <i>k</i> = 4). Where Ramanujan’s 1729 represents an order-2 collision (<i>r</i> = 2) of third powers, Ashfaque isolates an extraordinary **order-4 primitive collision (<i>r</i> = 4)** of fourth powers.

> [!IMPORTANT]
> **Note on Geometric Terminology:** In metric mathematics, "Taxicab Geometry" often refers to the non-Euclidean <i>L</i><sub>1</sub> Manhattan distance metric. However, within Diophantine geometry and algebraic varieties (the focus of this paper), **1729** serves as the prototype for *Taxicab-type coincidence problems*. It establishes the fundamental geometric principle of finding multiple distinct rational points intersecting on a single algebraic hypersurface.

<hr>

## 2. Historical & Theoretical Context

The search for non-trivial integer solutions to equal sums of like powers is a foundational driver of modern number theory. This repository builds upon a rich timeline of mathematical breakthroughs:

* **Euler's Sum of Powers Conjecture (1769):** Leonhard Euler generalized Fermat's Last Theorem by proposing that at least *k* *k*-th powers are required to sum to a *k*-th power.
* **Lander & Parkin (1966):** Discovered a monumental counterexample to Euler's conjecture for *k* = 5, isolating the equality <code>27<sup>5</sup> + 84<sup>5</sup> + 110<sup>5</sup> + 133<sup>5</sup> = 144<sup>5</sup></code>.
* **Elkies & Frye (1986):** Noam Elkies provided an analytical disproof for *k* = 4, which directly enabled Roger Frye to computationally isolate the minimal counterexample solution <code>95800<sup>4</sup> + 217519<sup>4</sup> + 414560<sup>4</sup> = 422481<sup>4</sup></code>.
* **Ashfaque (2026):** Establishes that the multi-variable parameter space for *m* = 3 and *k* = 4 permits dense, multi-way primitive coincidences where a single invariant scalar *S* is simultaneously expressed by multiple distinct triplets.

<hr>

## 3. The Minimal Invariant Quadruplet (*S* = 5,978,882)

In a systematic computational sweep bounded by an upper limit of *N* = 100, an exceptional four-way primitive collision (*r* = 4) was successfully isolated. The minimal invariant sum is evaluated as:

<p align="center">
<code><i>S</i> = 5,978,882</code>
</p>

### Rigorous Numerical Verification & Coprimality
To certify that this four-way collision is strictly primitive—meaning it does not derive from modular scaling of smaller base configurations—each generating vector must satisfy coprimality. The four unique primitive fibers mapping directly to *S* are detailed below:

| Triplet Identifier | Primitive Vector (<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>x</i><sub>3</sub>) | Expanded Biquadratic Terms (<i>x</i><sub>1</sub><sup>4</sup> + <i>x</i><sub>2</sub><sup>4</sup> + <i>x</i><sub>3</sub><sup>4</sup>) | Coprimality Proof (gcd = 1) | Invariant Sum (<i>S</i>) |
| :--- | :--- | :--- | :--- | :--- |
| **Triplet A** | <code>(3, 40, 43)</code> | <code>81 + 2,560,000 + 3,418,801</code> | <code>gcd(3, 40, 43) = gcd(1, 43) = 1</code> | <code>5,978,882</code> |
| **Triplet B** | <code>(8, 37, 45)</code> | <code>4,096 + 1,874,161 + 4,100,625</code> | <code>gcd(8, 37, 45) = gcd(1, 45) = 1</code> | <code>5,978,882</code> |
| **Triplet C** | <code>(15, 32, 47)</code> | <code>50,625 + 1,048,576 + 4,879,681</code> | <code>gcd(15, 32, 47) = gcd(1, 47) = 1</code> | <code>5,978,882</code> |
| **Triplet D** | <code>(23, 25, 48)</code> | <code>279,841 + 390,625 + 5,308,416</code> | <code>gcd(23, 25, 48) = gcd(1, 48) = 1</code> | <code>5,978,882</code> |

<hr>

## 4. Search Methodology & Algorithmic Architecture

Let &#8468; define the set of ordered primitive triplets:

<p align="center">
<code>&#8468; = {(<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>x</i><sub>3</sub>) &in; &#8469;<sup>3</sup> | 1 &le; <i>x</i><sub>1</sub> &lt; <i>x</i><sub>2</sub> &lt; <i>x</i><sub>3</sub>, gcd = 1}</code>
</p>

We define the biquadratic evaluation mapping *f*: &#8468; &rarr; &#8469; via:

<p align="center">
<code><i>f</i>(<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>x</i><sub>3</sub>) = <i>x</i><sub>1</sub><sup>4</sup> + <i>x</i><sub>2</sub><sup>4</sup> + <i>x</i><sub>3</sub><sup>4</sup></code>
</p>

A multi-way primitive collision of order *r* occurs when there exists an invariant sum *S* such that the fiber *f*<sup>&minus;1</sup>(*S*) contains exactly *r* distinct triplets.

### Memory-Efficient Meet-in-the-Middle Strategy
To systematically hunt for these solutions up to an arbitrary upper bound max(<i>x</i><sub>3</sub>) &le; *N*, this codebase implements a hash-mapped **Meet-in-the-Middle architecture**.

* **Pairwise Optimization:** By incrementally restricting calculations via the strict pairwise coprimality criteria <code>gcd(gcd(<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>), <i>x</i><sub>3</sub>) = 1</code>, the cardinality of the searched parameter space is dramatically reduced.
* **Complexity:** This optimization reduces search execution time to <code><i>O</i>(<i>N</i><sup>3</sup>)</code> while maintaining constant-time <code><i>O</i>(1)</code> associative lookups.

<hr>

## 5. Geometric Interpretation & Algebraic Varieties

Geometrically, each primitive triplet represents an integer point on the 3-dimensional affine hypersurface defined over &#8474; by the quartic equation:

<p align="center">
<code><i>X</i><sup>4</sup> + <i>Y</i><sup>4</sup> + <i>Z</i><sup>4</sup> = <i>S</i></code>
</p>

The isolation of an order-4 collision proves that for the specific level set *S* = 5,978,882, this quartic surface contains **at least 24 rational points** when accounting for sign permutations and coordinate permutations across the octants.

Furthermore, these intersecting pairs correspond to integer vectors on the higher-dimensional intersection variety:

<p align="center">
<code><i>X</i><sub>1</sub><sup>4</sup> + <i>X</i><sub>2</sub><sup>4</sup> + <i>X</i><sub>3</sub><sup>4</sup> = <i>Y</i><sub>1</sub><sup>4</sup> + <i>Y</i><sub>2</sub><sup>4</sup> + <i>Y</i><sub>3</sub><sup>4</sup> = <i>Z</i><sub>1</sub><sup>4</sup> + <i>Z</i><sub>2</sub><sup>4</sup> + <i>Z</i><sub>3</sub><sup>4</sup> = <i>W</i><sub>1</sub><sup>4</sup> + <i>W</i><sub>2</sub><sup>4</sup> + <i>W</i><sub>3</sub><sup>4</sup></code>
</p>

Because rational points are notoriously sparse on surfaces of general type, the existence of an isolated scalar like *S* = 5,978,882 indicates deep arithmetic instabilities or specializations of elliptic curves mapped onto the hypersurface components.

<hr>

## 6. Future Research Directions

The explicit verification of the *S* = 5,978,882 quadruplet opens several critical avenues for advanced analytic and computational work:

1. **Parametric Families:** Determining whether an infinite family of primitive 4-way biquadratic collisions can be generated parametrically.
2. **Elliptic Curve Ranks:** Investigating the corresponding elliptic curves on the underlying surfaces to search for higher-order algebraic ranks.
3. **Order-5 Hunting:** Pushing computational boundaries and algorithmic efficiency toward finding the world's first order-5 primitive collision (*r* = 5).

<hr>

## 7. Repository Structure & Usage

* `src/`: Contains the C++/Rust implementations of the memory-efficient <i>O</i>(<i>N</i><sup>3</sup>) Meet-in-the-Middle search algorithms.
* `data/`: Exported logs of verified primitive fibers and invariant sums.
* `docs/`: Mathematical proofs, LaTeX sources of Ashfaque's research note, and geometric variety plots.
