<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Multi-Way Primitive Diophantine Coincidences for Biquadratic Triplets</title>
  <style>
    :root {
      --color-canvas-default: #ffffff;
      --color-fg-default: #1f2328;
      --color-fg-muted: #656d76;
      --color-border-default: #d0d7de;
      --color-neutral-muted: rgba(175, 184, 193, 0.2);
      --color-canvas-subtle: #f6f8fa;
    }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
      font-size: 16px;
      line-height: 1.6;
      color: var(--color-fg-default);
      background-color: var(--color-canvas-default);
      margin: 0;
      padding: 2rem;
      display: flex;
      justify-content: center;
    }
    .markdown-body {
      max-width: 900px;
      width: 100%;
    }
    h1, h2, h3 {
      margin-top: 24px;
      margin-bottom: 16px;
      font-weight: 600;
    }
    h1 { font-size: 2em; border-bottom: 1px solid var(--color-border-default); padding-bottom: .3em; }
    h2 { font-size: 1.5em; border-bottom: 1px solid var(--color-border-default); padding-bottom: .3em; }
    h3 { font-size: 1.25em; }
    p, blockquote, ul, ol, table { margin-top: 0; margin-bottom: 16px; }
    blockquote {
      padding: 0.5em 1em;
      color: var(--color-fg-muted);
      border-left: .25em solid var(--color-border-default);
      background-color: var(--color-canvas-subtle);
      border-radius: 0 6px 6px 0;
    }
    code {
      padding: .2em .4em;
      font-size: 85%;
      background-color: var(--color-neutral-muted);
      border-radius: 6px;
      font-family: monospace;
    }
    .equation {
      display: block;
      text-align: center;
      margin: 1.5em 0;
      padding: 1em;
      background-color: var(--color-canvas-subtle);
      border-radius: 6px;
      overflow-x: auto;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      margin-bottom: 16px;
    }
    table th, table td {
      padding: 6px 13px;
      border: 1px solid var(--color-border-default);
    }
    table th { background-color: var(--color-canvas-subtle); text-align: left; }
    table tr:nth-child(2n) { background-color: var(--color-canvas-subtle); }
    hr { height: .25em; margin: 24px 0; background-color: var(--color-border-default); border: 0; }
  </style>
</head>
<body>
  <article class="markdown-body">
    <h1>Multi-Way Primitive Diophantine Coincidences for Biquadratic Triplets</h1>

    <blockquote cite="1">
      <p><strong>Paper Title:</strong> Computational Investigation of Multi-Way Primitive Diophantine Coincidences for Biquadratic Triplets[cite: 1]</p>
      <p><strong>Author:</strong> Johar M. Ashfaque[cite: 1]</p>
      <p><strong>Date:</strong> July 3, 2026[cite: 1]</p>
      <p><strong>Primary Discovery:</strong> Isolation of an exceptional 4-way primitive Diophantine collision for the sum of three fourth powers sharing the minimal invariant sum <i>S</i> = 5,978,882[cite: 1].</p>
    </blockquote>

    <hr>

    <h2>1. The 1729 Connection: From Ramanujan to Biquadratic Hypersurfaces</h2>
    <p>To understand the core significance of this repository and Ashfaque's computational discoveries, one must first look at <strong>1729</strong>—the famous <strong>Hardy-Ramanujan number</strong>. Historically, 1729 is the smallest positive integer that can be expressed as the sum of two positive cubes in two distinct ways:</p>

    <div class="equation">
      <code>1<sup>3</sup> + 12<sup>3</sup> = 9<sup>3</sup> + 10<sup>3</sup> = 1729</code>
    </div>

    <p>In number theory and Diophantine geometry, 1729 lies at the foundational heart of <strong>Taxicab-type problems</strong>[cite: 1]. These problems seek integer solutions to equal sums of like powers, mathematically generalized as[cite: 1]:</p>

    <div class="equation">
      <code>&Sigma;<sub><i>i</i>=1</sub><sup><i>m</i></sup> <i>x<sub>i</sub><sup>k</sup></i> = &Sigma;<sub><i>j</i>=1</sub><sup><i>m</i></sup> <i>y<sub>j</sub><sup>k</sup></i></code>
    </div>

    <p>While classical Taxicab numbers (beginning with 1729) explore two-summand cubic equations (<i>m</i> = 2, <i>k</i> = 3) which have been extensively cataloged over the centuries[cite: 1], Ashfaque's work pushes this conceptual framework into a much less charted structural topology[cite: 1].</p>
    
    <p>Specifically, this research investigates <strong>three-summand biquadratic equations</strong> (<i>m</i> = 3, <i>k</i> = 4)[cite: 1]. Where Ramanujan’s 1729 represents an order-2 collision (<i>r</i> = 2) of third powers, Ashfaque isolates an extraordinary <strong>order-4 primitive collision (<i>r</i> = 4)</strong> of fourth powers[cite: 1].</p>

    <blockquote>
      <p><strong>Note on Geometric Terminology:</strong> In metric mathematics, "Taxicab Geometry" often refers to the non-Euclidean <i>L</i><sub>1</sub> Manhattan distance metric. However, within Diophantine geometry and algebraic varieties (the focus of this paper), <strong>1729</strong> serves as the prototype for <em>Taxicab-type coincidence problems</em>[cite: 1]. It establishes the fundamental geometric principle of finding multiple distinct rational points intersecting on a single algebraic hypersurface[cite: 1].</p>
    </blockquote>

    <hr>

    <h2>2. Historical &amp; Theoretical Context</h2>
    <p>The search for non-trivial integer solutions to equal sums of like powers is a foundational driver of modern number theory[cite: 1]. This repository builds upon a rich timeline of mathematical breakthroughs:</p>

    <ul>
      <li><strong>Euler's Sum of Powers Conjecture (1769):</strong> Leonhard Euler generalized Fermat's Last Theorem by proposing that at least <i>k</i> <i>k</i>-th powers are required to sum to a <i>k</i>-th power[cite: 1].</li>
      <li><strong>Lander &amp; Parkin (1966):</strong> Discovered a monumental counterexample to Euler's conjecture for <i>k</i> = 5, isolating the equality <code>27<sup>5</sup> + 84<sup>5</sup> + 110<sup>5</sup> + 133<sup>5</sup> = 144<sup>5</sup></code>[cite: 1].</li>
      <li><strong>Elkies &amp; Frye (1986):</strong> Noam Elkies provided an analytical disproof for <i>k</i> = 4, which directly enabled Roger Frye to computationally isolate the minimal counterexample solution <code>95800<sup>4</sup> + 217519<sup>4</sup> + 414560<sup>4</sup> = 422481<sup>4</sup></code>[cite: 1].</li>
      <li><strong>Ashfaque (2026):</strong> Establishes that the multi-variable parameter space for <i>m</i> = 3 and <i>k</i> = 4 permits dense, multi-way primitive coincidences where a single invariant scalar <i>S</i> is simultaneously expressed by multiple distinct triplets[cite: 1].</li>
    </ul>

    <hr>

    <h2>3. The Minimal Invariant Quadruplet (<i>S</i> = 5,978,882)</h2>
    <p>In a systematic computational sweep bounded by an upper limit of <i>N</i> = 100, an exceptional four-way primitive collision (<i>r</i> = 4) was successfully isolated[cite: 1]. The minimal invariant sum is evaluated as[cite: 1]:</p>

    <div class="equation">
      <code><i>S</i> = 5,978,882</code>
    </div>

    <h3>Rigorous Numerical Verification &amp; Coprimality</h3>
    <p>To certify that this four-way collision is strictly primitive—meaning it does not derive from modular scaling of smaller base configurations—each generating vector must satisfy coprimality[cite: 1]. The four unique primitive fibers mapping directly to <i>S</i> are detailed below[cite: 1]:</p>

    <table>
      <thead>
        <tr>
          <th>Triplet Identifier</th>
          <th>Primitive Vector (<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>x</i><sub>3</sub>)</th>
          <th>Expanded Biquadratic Terms (<i>x</i><sub>1</sub><sup>4</sup> + <i>x</i><sub>2</sub><sup>4</sup> + <i>x</i><sub>3</sub><sup>4</sup>)</th>
          <th>Coprimality Proof (gcd = 1)</th>
          <th>Invariant Sum (<i>S</i>)</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>Triplet A</strong>[cite: 1]</td>
          <td><code>(3, 40, 43)</code>[cite: 1]</td>
          <td><code>81 + 2,560,000 + 3,418,801</code>[cite: 1]</td>
          <td><code>gcd(3, 40, 43) = gcd(1, 43) = 1</code>[cite: 1]</td>
          <td><code>5,978,882</code>[cite: 1]</td>
        </tr>
        <tr>
          <td><strong>Triplet B</strong>[cite: 1]</td>
          <td><code>(8, 37, 45)</code>[cite: 1]</td>
          <td><code>4,096 + 1,874,161 + 4,100,625</code>[cite: 1]</td>
          <td><code>gcd(8, 37, 45) = gcd(1, 45) = 1</code>[cite: 1]</td>
          <td><code>5,978,882</code>[cite: 1]</td>
        </tr>
        <tr>
          <td><strong>Triplet C</strong>[cite: 1]</td>
          <td><code>(15, 32, 47)</code>[cite: 1]</td>
          <td><code>50,625 + 1,048,576 + 4,879,681</code>[cite: 1]</td>
          <td><code>gcd(15, 32, 47) = gcd(1, 47) = 1</code>[cite: 1]</td>
          <td><code>5,978,882</code>[cite: 1]</td>
        </tr>
        <tr>
          <td><strong>Triplet D</strong>[cite: 1]</td>
          <td><code>(23, 25, 48)</code>[cite: 1]</td>
          <td><code>279,841 + 390,625 + 5,308,416</code>[cite: 1]</td>
          <td><code>gcd(23, 25, 48) = gcd(1, 48) = 1</code>[cite: 1]</td>
          <td><code>5,978,882</code>[cite: 1]</td>
        </tr>
      </tbody>
    </table>

    <hr>

    <h2>4. Search Methodology &amp; Algorithmic Architecture</h2>
    <p>Let &#8468; define the set of ordered primitive triplets[cite: 1]:</p>

    <div class="equation">
      <code>&#8468; = {(<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>x</i><sub>3</sub>) &in; &#8469;<sup>3</sup> | 1 &le; <i>x</i><sub>1</sub> &lt; <i>x</i><sub>2</sub> &lt; <i>x</i><sub>3</sub>, gcd = 1}</code>
    </div>

    <p>We define the biquadratic evaluation mapping <i>f</i>: &#8468; &rarr; &#8469; via[cite: 1]:</p>

    <div class="equation">
      <code><i>f</i>(<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>x</i><sub>3</sub>) = <i>x</i><sub>1</sub><sup>4</sup> + <i>x</i><sub>2</sub><sup>4</sup> + <i>x</i><sub>3</sub><sup>4</sup></code>
    </div>

    <p>A multi-way primitive collision of order <i>r</i> occurs when there exists an invariant sum <i>S</i> such that the fiber <i>f</i><sup>&minus;1</sup>(<i>S</i>) contains exactly <i>r</i> distinct triplets[cite: 1].</p>

    <h3>Memory-Efficient Meet-in-the-Middle Strategy</h3>
    <p>To systematically hunt for these solutions up to an arbitrary upper bound max(<i>x</i><sub>3</sub>) &le; <i>N</i>, this codebase implements a hash-mapped <strong>Meet-in-the-Middle architecture</strong>[cite: 1].</p>

    <ul>
      <li><strong>Pairwise Optimization:</strong> By incrementally restricting calculations via the strict pairwise coprimality criteria <code>gcd(gcd(<i>x</i><sub>1</sub>, <i>x</i><sub>2</sub>), <i>x</i><sub>3</sub>) = 1</code>, the cardinality of the searched parameter space is dramatically reduced[cite: 1].</li>
      <li><strong>Complexity:</strong> This optimization reduces search execution time to <code><i>O</i>(<i>N</i><sup>3</sup>)</code> while maintaining constant-time <code><i>O</i>(1)</code> associative lookups[cite: 1].</li>
    </ul>

    <hr>

    <h2>5. Geometric Interpretation &amp; Algebraic Varieties</h2>
    <p>Geometrically, each primitive triplet represents an integer point on the 3-dimensional affine hypersurface defined over &#8474; by the quartic equation[cite: 1]:</p>

    <div class="equation">
      <code><i>X</i><sup>4</sup> + <i>Y</i><sup>4</sup> + <i>Z</i><sup>4</sup> = <i>S</i></code>
    </div>

    <p>The isolation of an order-4 collision proves that for the specific level set <i>S</i> = 5,978,882, this quartic surface contains <strong>at least 24 rational points</strong> when accounting for sign permutations and coordinate permutations across the octants[cite: 1].</p>

    <p>Furthermore, these intersecting pairs correspond to integer vectors on the higher-dimensional intersection variety[cite: 1]:</p>

    <div class="equation">
      <code><i>X</i><sub>1</sub><sup>4</sup> + <i>X</i><sub>2</sub><sup>4</sup> + <i>X</i><sub>3</sub><sup>4</sup> = <i>Y</i><sub>1</sub><sup>4</sup> + <i>Y</i><sub>2</sub><sup>4</sup> + <i>Y</i><sub>3</sub><sup>4</sup> = <i>Z</i><sub>1</sub><sup>4</sup> + <i>Z</i><sub>2</sub><sup>4</sup> + <i>Z</i><sub>3</sub><sup>4</sup> = <i>W</i><sub>1</sub><sup>4</sup> + <i>W</i><sub>2</sub><sup>4</sup> + <i>W</i><sub>3</sub><sup>4</sup></code>
    </div>

    <p>Because rational points are notoriously sparse on surfaces of general type, the existence of an isolated scalar like <i>S</i> = 5,978,882 indicates deep arithmetic instabilities or specializations of elliptic curves mapped onto the hypersurface components[cite: 1].</p>

    <hr>

    <h2>6. Future Research Directions</h2>
    <p>The explicit verification of the <i>S</i> = 5,978,882 quadruplet opens several critical avenues for advanced analytic and computational work[cite: 1]:</p>

    <ol>
      <li><strong>Parametric Families:</strong> Determining whether an infinite family of primitive 4-way biquadratic collisions can be generated parametrically[cite: 1].</li>
      <li><strong>Elliptic Curve Ranks:</strong> Investigating the corresponding elliptic curves on the underlying surfaces to search for higher-order algebraic ranks[cite: 1].</li>
      <li><strong>Order-5 Hunting:</strong> Pushing computational boundaries and algorithmic efficiency toward finding the world's first order-5 primitive collision (<i>r</i> = 5)[cite: 1].</li>
    </ol>

    <hr>

    <h2>7. Repository Structure &amp; Usage</h2>
    <ul>
      <li><code>src/</code>: Contains the C++/Rust implementations of the memory-efficient <i>O</i>(<i>N</i><sup>3</sup>) Meet-in-the-Middle search algorithms.</li>
      <li><code>data/</code>: Exported logs of verified primitive fibers and invariant sums.</li>
      <li><code>docs/</code>: Mathematical proofs, LaTeX sources of Ashfaque's research note[cite: 1], and geometric variety plots.</li>
    </ul>
  </article>
</body>
</html>
