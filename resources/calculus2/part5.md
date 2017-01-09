---
layout: page
title: "Part 5: Sequences and Series"
---

---

\\(
  \newcommand{\\<}{\langle}
  \newcommand{\\>}{\rangle}
\\) <!-- TODO make angle brackets parentheses -->

## 5.1 Sequences

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.1

### 5.1.1 Definition

<iframe width="560" height="315" src="https://www.youtube.com/embed/vx3XB5mz7UY" frameborder="0" allowfullscreen></iframe>

- A sequence is an infinitely long list of real numbers. For example,
  the sequence of positive even integers is \\(\\<2,4,6,8,\dots\\>\\).
- **Example**
  Use your intuition to guess the next three terms of the sequences
  \\(\\<1,3,5,7,9,\dots\\>\\),
  \\(\\<3,-6,9,-12,15,\dots\\>\\), and
  \\(\\<0,1,4,9,16,\dots\\>\\).
- An explicit formula \\(a_n\\) is a rule defining each term of the
  sequence, where \\(n=0\\) yields the first term, \\(n=1\\) gives the
  next term, and so on. The sequence generated by the formula \\(a_n\\)
  is written as
  \\(\\<a_n\\>\_{n=0}^\infty=\\<a_0,a_1,a_2,\dots\\>\\).
    - Occasionally the first term of the sequence
      may be given by an integer different from \\(0\\), in which case
      the sequence is written like
      \\(\\<a_n\\>\_{n=1}^\infty\\).
- **Example**
  Write the first five terms of the sequences
  \\(\\<a_n\\>\_{n=0}^\infty\\),
  \\(\\<b_n\\>\_{n=0}^\infty\\), and
  \\(\\<c_n\\>\_{n=0}^\infty\\)
  defined by
  \\(a_n=4n\\),
  \\(b_n=\frac{(-1)^n}{n^2+2}\\), and
  \\(c_n=\cos(\frac{\pi}{2}n)\\).
- **Example** Give the term \\(a_7\\) for the sequence defined by
  the formula \\(a_n=\frac{n}{2n+1}\\).
  <!-- TODO replace previous with create a formula question -->


### 5.1.2 Recursive Formulas

<iframe width="560" height="315" src="https://www.youtube.com/embed/qxtFf3g1DNI" frameborder="0" allowfullscreen></iframe>

- A recursive formula for a sequence defines one or more initial terms of
  the sequence, and then defines future terms of the sequence by using
  previous terms.
- **Example** Write the first ten terms of the Fibonacci sequence defined
  by the recursive formula \\(f_0=1,f_1=1,f_{n+2}=f_n+f_{n+1}\\).
- **Example** Write the first six terms of the factorial sequence defined
  by the recursive formula \\(!\_0=1,!\_{n+1}=(n+1)!\_n\\).
- The factorial sequence is commonly written in the form \\(n!\\) rather
  than \\(!\_n\\). It has the explicit formula
  \\(n!=1\times2\times3\times\dots\times n\\).
- **Example** Prove that \\(a_n=\frac{3}{2^n}\\)
  is an explicit formula for the
  sequence \\(\\<a_n\\>\_{n=0}^\infty\\) defined recursively by
  \\(a_0=3,a_{n+1}=\frac{a_n}{2}\\).

### 5.1.3 Limits, Convergence, and Divergence

<iframe width="560" height="315" src="https://www.youtube.com/embed/5Zqwo5dZAaU" frameborder="0" allowfullscreen></iframe>

- The sequence \\(\\<a_n\\>\_{n=i}^\infty\\) converges to a limit
  \\(L\\) if for each \\(\epsilon>0\\), there exists an integer \\(N\\)
  such that \\(\|a_n-L\|<\epsilon\\) for all \\(n\geq N\\).
  This is written as \\(\lim_{n\to\infty}a_n=L\\) or
  \\(a_n\to L\\).
- **Example** Guess the limit of the harmonic sequence    
  \\(\\<a_n\\>\_{n=1}^\infty\\) defined by \\(a_n=\frac{1}{n}\\)
  by writing out the first few terms.
- **Example** Guess the limit of the sequence    
  defined by \\(g_n=\frac{2^n}{2^{n+1}}\\)
  by writing out the first few terms.
- A sequence diverges when it doesn't converge to any limit.
- **Example** Write a few terms of the sequence defined by the formula
  \\(b_n=(-1)^n\frac{n+1}{n+2}\\). Does it appear to be converging or
  diverging?

### Exercises for 5.1

1.  Use your intuition to guess the next three terms of the sequences
    \\(\\<1,5,9,13,17,\dots\\>\\),
    \\(\\<1,\frac{1}{4},\frac{1}{9},\frac{1}{16},\frac{1}{25},\dots\\>\\), and
    \\(\\<\frac{1}{3},-1,3,-9,27,\dots\\>\\).
1.  Create an explicit formula for each of the three previous sequences.
1.  Write the first five terms of the sequences
    \\(\\<a_n\\>\_{n=0}^\infty\\),
    \\(\\<b_n\\>\_{n=0}^\infty\\), and
    \\(\\<c_n\\>\_{n=0}^\infty\\)
    defined by
    \\(a_n=3n+2\\),
    \\(b_n=2(-\frac{1}{3})^n\\), and
    \\(c_n=\frac{n}{1+n^2}\\).
1.  Write the first six terms of the sequence \\(\\<q_n\\>\_{n=0}^\infty\\)
    defined by \\(q_0=0\\) and \\(q_{n+1}=q_n+2n+1\\).
1.  Prove that \\(q_n=n^2\\) is an explicit formula for the
    sequence defined recursively in the previous problem.
1.  Write the first six terms of the sequence \\(\\<b_n\\>\_{n=1}^\infty\\)
    defined by \\(b_1=4\\) and \\(b_{n+1}=\frac{b_n}{2}\\).
1.  Prove that \\(b_n=\frac{8}{2^n}\\) is an explicit formula for the
    sequence defined recursively in the previous problem.
1.  Guess the limit of the alternating harmonic sequence    
    \\(\\<b_n\\>\_{n=1}^\infty\\) defined by \\(b_n=\frac{(-1)^n}{n}\\)
    by writing out the first few terms.
1.  Guess the limit of the geometric sequence    
    \\(\\<g_n\\>\_{n=0}^\infty\\) defined by \\(g_n=2^{-n}\\)
    by writing out the first few terms.
1.  Guess the limit of the sequence    
    \\(\\<a_n\\>\_{n=3}^\infty\\) defined by \\(a_n=\frac{3n+2}{2n+1}\\)
    by writing out the first few terms.
1.  Write a few terms of the sequence defined by the formula
    \\(c_n=\frac{n!}{n^2+1}\\). Does it appear to be converging or
    diverging?
1.  Write a few terms of the sequence defined by the formula
    \\(s_n=\sin(\frac{\pi n}{3})\\). Does it appear to be converging or
    diverging?
1.  (OPTIONAL)
    Sketch a picture which explains why
    \\(\lim_{n\to\infty} \sin(\pi n)=0\\) as the limit of a
    sequence, but \\(\lim_{x\to\infty}\sin(\pi x)\\)
    does not exist as a limit of a function.
1.  (QUIZ)
    What are the first five terms of the sequence \\(\\<r_n\\>\_{n=1}^\infty\\)
    defined explicitly by \\(r_n=\frac{n+2}{3+n^2}\\)?
    - \\(\\<\frac{3}{4},\frac{4}{7},\frac{5}{12},\frac{6}{19}, \frac{1}{4},\dots\\>\\)
    - \\(\\<\frac{2}{7},\frac{1}{2},\frac{4}{9},0,\frac{5}{17},\dots\\>\\)
    - \\(\\<0,\frac{3}{5},\frac{5}{18},\frac{8}{27},\frac{9}{61},\dots\\>\\)
1.  (QUIZ)
    What are the first five terms of the sequence \\(\\<w_n\\>\_{n=0}^\infty\\)
    defined recursively by \\(w_0=1\\), \\(w_1=2\\),
    \\(w_{n+2}=2w_n+w_{n+1}\\)?
    - \\(\\<1,2,5,10,17,\dots\\>\\)
    - \\(\\<1,2,3,5,9,\dots\\>\\)
    - \\(\\<1,2,4,8,16,\dots\\>\\)
1.  (QUIZ)
    Which of these statements seems most appropriate for describing the
    sequence whose initial terms are
    \\(\\<1,\frac{3}{4},\frac{5}{8},\frac{9}{16},\frac{17}{32},\dots\\>\\)?
    - The sequence appears to converge to \\(\frac{1}{2}\\).
    - The sequence appears to diverge to \\(\frac{1}{2}\\).
    - The sequence appears to neither converge nor diverge.

[Solutions 1-7]({{site.baseurl}}public/solutions/5.1a.pdf)

[Solutions 8-16]({{site.baseurl}}public/solutions/5.1b.pdf)


---

## 5.2 Computing Limits of Sequences

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.1

### 5.2.1 Limits of Sequences and Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/lEqbxJeq9_M" frameborder="0" allowfullscreen></iframe>

- If \\(f(x)\\) is a function and \\(a_n\\) is a sequence such that
  \\(f(n)=a_n\\) for sufficiently large integers \\(n\\), then
  \\(\lim_{x\to\infty}f(x)=L\\) implies \\(\lim_{n\to\infty}a_n=L\\).
- Therefore all the rules for evaluating \\(\lim_{x\to\infty}f(x)\\)
  extend to evaluating \\(\lim_{n\to\infty}a_n\\).
- **Example** Use factoring to compute
  \\(\lim_{n\to\infty}\frac{4+n}{n^3+1}\\).
- **Example** Use L'Hopital's Rule to prove that any sequence
  defined by the formula \\(a_n=\frac{n^2+3}{4-5n^2}\\) converges to
  \\(-\frac{1}{5}\\).
- **Example** Use the squeeze theorem to compute
  \\(\lim_{n\to\infty}\frac{\sin n}{n}\\).

### 5.2.2 Common Limits

<iframe width="560" height="315" src="https://www.youtube.com/embed/--o02u0BdUo" frameborder="0" allowfullscreen></iframe>

- The following limits are often useful:
    - \\(\lim_{n\to\infty} x = x\\)
    - \\(\lim_{n\to\infty} \frac{1}{n} = 0\\)
    - \\(\lim_{n\to\infty} \frac{\ln n}{n} = 0\\)
    - \\(\lim_{n\to\infty} \sqrt[n]{p(n)} = 1\\) where \\(p(n)\\)
      is a polynomial
    - \\(\lim_{n\to\infty} x^n = 0\\), \\(\|x\|<1\\)
    - \\(\lim_{n\to\infty} (1+\frac{x}{n})^n=e^x\\)
    - \\(\lim_{n\to\infty} \frac{x^n}{n!}=0\\)
- **Example** Find \\(\lim_{n\to\infty}\frac{\ln(n^3)}{n}\\).
- **Example** Find \\(\lim_{n\to\infty}\frac{3^n+1}{n!}\\).
- **Example** Find \\(\lim_{n\to\infty}(4n)^{1/n}\\).

### 5.2.3 Monotonic and Bounded Sequences

<iframe width="560" height="315" src="https://www.youtube.com/embed/fVx-4y-N-P0" frameborder="0" allowfullscreen></iframe>

- A sequence \\(\\<a_n\\>\_{n=i}^\infty\\) is bounded if there exist
  real numbers \\(A,B\\) such that \\(A\leq a_n\leq B\\) for all integers
  \\(n\geq i\\).
- **Example** Is the sequence \\(\\<a_n\\>\_{n=1}^\infty\\)
  where \\(a_n=\frac{n+1}{n}\\) bounded?
- **Example** Is the sequence \\(\\<b_n\\>\_{n=0}^\infty\\)
  given by \\(b_n=\frac{n}{(-3)^n}\\) bounded?
- A sequence is monotonic if it either never increases or never decreases.
- **Example** Is the sequence \\(\\<a_n\\>\_{n=1}^\infty\\)
  where \\(a_n=\frac{n+1}{n}\\) monotonic?
- **Example** Is the sequence \\(\\<b_n\\>\_{n=0}^\infty\\)
  given by \\(b_n=\frac{n}{(-3)^n}\\) monotonic?
- The Monotonic Sequence Theorem states that
  all bounded monotonic sequences converge.

### Exercises for 5.2

1.  Use factoring to compute
    \\(\displaystyle\lim_{n\to\infty}\frac{n-4n^2}{2n^2+7}\\).
1.  Use L'Hopital's Rule to prove that
    \\(\displaystyle\frac{\ln n}{n}\to 0\\).
1.  Use the squeeze theorem to compute
    \\(\displaystyle\lim_{n\to\infty}\frac{\cos n}{n\ln n}\\).
1.  Find \\(\displaystyle\lim_{n\to\infty}\frac{\sin n + 3n^2}{n^2+1}\\).
1.  Find \\(\displaystyle\lim_{n\to\infty}\frac{\ln(n^n)}{n^2}\\).
1.  Find \\(\displaystyle\lim_{n\to\infty}(5n^3)^{2/n}\\).
1.  Find \\(\displaystyle\lim_{n\to\infty}(\frac{1}{\pi})^{3n}\\).
1.  Find \\(\displaystyle\lim_{n\to\infty}(\frac{1}{2}+\frac{1}{n})^n\\).
1.  Find
    \\(\displaystyle\lim_{n\to\infty}
    \frac{\frac{(n+2)!}{2^n}}{\frac{3n^2n!}{2^{n+1}}}\\).
1.  Based on its first few terms, does the sequence
    \\(\\<a_n\\>\_{n=2}^\infty\\)
    where \\(a_n=\frac{2+n^2}{n^2-1}\\) appear bounded? Monotonic?
    Does it appear to converge?
1.  Based on its first few terms, does the sequence
    \\(\\<b_n\\>\_{n=0}^\infty\\)
    where \\(b_n=(-3)^n\\) appear bounded? Monotonic?
    Does it appear to converge?
1.  Based on its first few terms, does the sequence
    \\(\\<y_n\\>\_{n=1}^\infty\\)
    where \\(y_n=(-\frac{1}{2})^n\\) appear bounded? Monotonic?
    Does it appear to converge?
1.  (OPTIONAL)
    Prove that \\(\displaystyle\lim_{n\to\infty} (1+\frac{x}{n})^n=e^x\\) by
    considering the function version
    \\(\displaystyle L=\lim_{t\to\infty} (1+\frac{x}{t})^t\\) and taking
    the natural log of both sides of the equality. Use L'Hopital
    to solve this limit, showing that \\(\ln L=x\\) and therefore
    \\(L=e^x\\).
1.  (QUIZ)
    Find \\(\lim_{n\to\infty}\frac{n!\cos n}{(n+1)!}\\).
    - \\(1\\)
    - \\(0\\)
    - \\(\pi/2\\)
1.  (QUIZ)
    Find \\(\lim_{n\to\infty}\frac{(3+n)^n}{n^n}\\).
    - \\(1\\)
    - \\(0\\)
    - \\(e^3\\)
1.  (QUIZ)
    Which of these statements seems most appropriate for describing the
    sequence whose initial terms are
    \\(\\<\frac{1}{4},-\frac{1}{6},\frac{1}{8},-\frac{1}{10},
    \frac{1}{12},\dots\\>\\)?
    - The sequence is bounded and monotonic, so it converges by
      the Monotonic Sequence Theorem.
    - The sequence is not monotonic and not bounded, so it diverges by
      the Monotonic Sequence Theorem.
    - The sequence is bounded, but not monotonic, so the Monotonic Sequence
      Theorem doesn't apply. However, it does
      appear to converge to \\(0\\) anyway.

[Solutions 1-13]({{site.baseurl}}public/solutions/5.2a.pdf)

[Solutions 14-16]({{site.baseurl}}public/solutions/5.2b.pdf)


---

## 5.3 Series

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.2

### 5.3.1 Series as Partial Sum Sequences

<iframe width="560" height="315" src="https://www.youtube.com/embed/docTkY5KEOI" frameborder="0" allowfullscreen></iframe>

- For a given sequence \\(\\<a_n\\>\_{n=0}^\infty\\), its
  partial sum sequence \\(\\<s_n\\>\_{n=0}^\infty\\) is defined explicitly
  by \\(s_n=\sum_{i=0}^n a_i=a_0+a_1+\dots+a_n\\), and defined recursively by
  \\(s_0=a_0\\) and \\(s_{n+1}=s_n+a_{n+1}\\).
- **Example** Write out the first few terms of the partial sum sequence for
  \\(\\<1,2,3,4,5,\dots\\>\\).
- **Example** Write out the first few terms of the partial sum sequence for
  \\(\\<b_i\\>\_{i=1}^\infty\\) where \\(b_i=\frac{6}{i}\\).
- The series \\(\sum_{n=0}^\infty a_n=a_0+a_1+a_2+\dots\\) represents the
  sum of the infinite sequence \\(\\<a_n\\>\_{n=0}^\infty\\). If its
  partial sum sequence converges to \\(L\\), then we say that its series
  converges to \\(L\\) and the value of the series is \\(L\\)
  (written \\(\sum_{n=0}^\infty a_n=a_0+a_1+a_2+\dots=L\\)). Otherwise,
  we say the series diverges.

### 5.3.2 Telescoping/Geometric Sequences and Series

<iframe width="560" height="315" src="https://www.youtube.com/embed/hI9SNAt7HMQ" frameborder="0" allowfullscreen></iframe>

- A telescoping series is a series whose partial sum sequence allows for
  canceling.
- **Example** Show that \\(\sum_{n=1}^\infty(\frac{1}{n}-\frac{1}{n+1})\\)
  converges to \\(1\\) by evaluating the limit of its partial sum sequence.
- **Example** Does \\(\sum_{n=0}^\infty\frac{2}{n^2+3n+2}\\) converge or
  diverge?

<iframe width="560" height="315" src="https://www.youtube.com/embed/mQ5GGR7YlQo" frameborder="0" allowfullscreen></iframe>

- The geometric series defined for real numbers \\(a,r\\) is
  \\(\sum_{n=0}^\infty ar^n=a+ar+ar^2+ar^3+\dots\\).
- The geometric series \\(\sum_{n=0}^\infty ar^n\\) converges to
  \\(\frac{a}{1-r}\\) when \\(|r|<1\\), and diverges when \\(|r|\geq 1\\).
- **Example** Compute \\(1+\frac{1}{2}+\frac{1}{4}+\frac{1}{8}+\dots\\).
- **Example** Does \\(\sum_{k=0}^\infty\frac{2}{3^{k+1}}\\) converge or
  diverge? If it converges, what is its value?
- **Example** Does \\(\sum_{k=0}^\infty\frac{2}{(1/3)^{k+1}}\\) converge or
  diverge? If it converges, what is its value?

### 5.3.3 Divergent Series

<iframe width="560" height="315" src="https://www.youtube.com/embed/zZreQ7WzkLs" frameborder="0" allowfullscreen></iframe>

- The Series Divergence Test: If a sequence fails to converge to \\(0\\),
  then its series diverges.
- **Example** Does \\(\sum_{k=0}^\infty\frac{k^2+3}{2k^2+k+5}\\) converge or
  diverge? If it converges, what is its value?
- This does NOT mean that if a sequence converges, then its series converges.
- The harmonic sequence \\(\\<\frac{1}{n}\\>\_{n=1}^\infty\\) converges to
  \\(0\\), but its series \\(\sum_{n=1}^\infty\frac{1}{n}\\) diverges.

### 5.3.4 Arithmetic Rules and Reindexing

<iframe width="560" height="315" src="https://www.youtube.com/embed/-_3H1IEtz0I" frameborder="0" allowfullscreen></iframe>

- Because a series is a limit, it follows the same rules as limits do.
- **Example** Evaluate the convergent series
  \\(\sum_{i=0}^\infty\frac{1+\frac{2^{i+2}}{i+1}-\frac{2^{i+2}}{i+2}}{2^i}\\).
- The starting index for a series may be adjusted by offsetting the index for
  its sequence in the opposite direction.
- **Example** Does \\(\sum_{m=-1}^\infty\frac{1}{m+2}\\) converge or
  diverge? If it converges, what is its value?

### Exercises for 5.3

1.  Write out the first four terms of the partial sum sequence for
    \\(\\<1,-\frac{1}{3},\frac{1}{9},-\frac{1}{27},\dots\\>\\).
1.  Write out the first four terms of the partial sum sequence for
    \\(\\<0.3,0.03,0.003,0.0003,\dots\\>\\).
1.  Does \\(\sum_{m=2}^\infty(\frac{3}{2m}-\frac{3}{2m+2})\\) converge or
    diverge? If it converges, what is its value?
1.  Does \\(\sum_{j=2}^\infty\frac{6}{4j^2+4j}\\) converge or
    diverge? If it converges, what is its value?
1.  Compute \\(1-\frac{1}{3}+\frac{1}{9}-\frac{1}{27}+\dots\\).
1.  Prove that \\(0.\overline3=0.333\dots\\) equals \\(\frac{1}{3}\\)
    by expressing the decimal
    expression as a geometric series.
1.  Write \\(0.\overline{27}=0.272727\dots\\) as a fraction of integers.
1.  Does \\(\sum_{n=0}^\infty\frac{6}{3^{n+2}}\\) converge or
    diverge? If it converges, what is its value?
1.  Does \\(\sum_{m=0}^\infty 3(-1)^m\\) converge or
    diverge? If it converges, what is its value?
1.  Does \\(\sum_{i=1}^\infty \frac{i+\sin i}{2i}\\) converge or
    diverge? If it converges, what is its value?
1.  Suppose \\(\sum_{n=0}^\infty a_n=3\\) and
    \\(\sum_{n=0}^\infty b_n=4\\). Evaluate
    \\(\sum_{n=0}^\infty(3a_n-2b_n)\\).
1.  Does \\(\sum_{k=2}^\infty 4(\frac{2}{3})^k\\) converge or
    diverge? If it converges, what is its value?
1.  (OPTIONAL) Prove \\(\sum_{n=1}^\infty\frac{1}{3^n}=\frac{1}{2}\\)
    using the proof of the Geometric Series formula (not the formula
    itself).
1.  (QUIZ)
    Does \\(\sum_{n=3}^\infty\left(\frac{6}{n}-\frac{6}{n+1}\right)\\)
    converge or diverge? If it converges, what is its value?
    - It converges to \\(\frac{1}{2}\\).
    - It converges to \\(2\\).
    - It diverges.
1.  (QUIZ)
    Does \\(\sum_{i=0}^\infty\frac{(-3)^i}{2}\\) converge or
    diverge? If it converges, what is its value?
    - It converges to \\(-3\\).
    - It converges to \\(6\\).
    - It diverges.
1.  (QUIZ)
    Does \\(\sum_{n=1}^\infty\frac{1}{4^n}\\) converge or
    diverge? If it converges, what is its value?
    - It converges to \\(\frac{1}{3}\\).
    - It converges to \\(\frac{3}{4}\\).
    - It diverges.


[Solutions 1-7]({{site.baseurl}}public/solutions/5.3a.pdf)

[Solutions 8-16]({{site.baseurl}}public/solutions/5.3b.pdf)




---

## 5.4 The Integral Test

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.3, 8.7

### 5.4.1 Improper Integrals

<iframe width="560" height="315" src="https://www.youtube.com/embed/xDj8Ne8ISHQ" frameborder="0" allowfullscreen></iframe>

- If \\(f(x)\geq 0\\), the improper integral
  \\(\int_a^\infty f(x)\,dx=\lim_{b\to\infty}\int_a^b f(x)\,dx\\)
  represents the area under the curve \\(y=f(x)\\) from \\(x=a\\) out
  to \\(\infty\\). If the limit exists,
  then the improper integral converges; otherwise it diverges.
- **Example** Does \\(\int_1^\infty\frac{1}{x^2}\,dx\\) converge or diverge?
  If it converges, what is its value?
- **Example** Does \\(\int_4^\infty\frac{1}{2\sqrt y}\,dy\\)
  converge or diverge?
  If it converges, what is its value?
- When an integrand is undefined at a bound of integration,
  then the integral is also called
  improper and is evaluated with a limit.
- **Example** Find the value of \\(\int_0^8 z^{-1/3}\,dz\\).

### 5.4.2 The Integral Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/Hbdj83xTMq4" frameborder="0" allowfullscreen></iframe>

- If \\(a_n=f(n)\\) where \\(f(x)\\) is a continuous, positive, decreasing
  function for sufficiently large values of \\(x\\), then
  the series \\(\sum_{n=N}^\infty a_n\\) and improper integral
  \\(\int_a^\infty f(x)\,dx\\) either both converge, or both diverge.
- **Example** Does \\(\sum_{n=4}^\infty\frac{4n+4}{n^2+2n+1}\\) converge or
  diverge?
- **Example** Does \\(\sum_{k=1}^\infty\frac{k}{e^{k^2}}\\) converge or diverge?
- Even when they both converge,
  the values of the series \\(\sum_{n=N}^\infty a_n\\) and improper integral
  \\(\int_N^\infty f(x)\,dx\\) usually differ.
- **Example** Show that
  \\(\sum_{n=1}^\infty\frac{1}{n^3}\not=\int_1^\infty\frac{1}{x^3}\,dx\\).

### 5.4.3 The \\(p\\)-Series Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/ceteDtCMKIg" frameborder="0" allowfullscreen></iframe>

- The \\(p\\)-Series Test states that the series
  \\(\sum_{n=1}^\infty\frac{1}{n^p}\\) converges when \\(p>1\\),
  and diverges when \\(p\leq 1\\).
- **Example**
  Does \\(\sum_{m=2}^\infty\frac{3}{\sqrt[10]{m^4}}\\) converge or diverge?
- **Example**
  Does \\(\sum_{j=0}^\infty\frac{1}{j^2+2j+1}\\) converge or diverge?

### Exercises for 5.4

1.  Does \\(\int_2^\infty\frac{32}{x^3}\,dx\\) converge or diverge?
    If it converges, what is its value?
1.  Does \\(\int_0^\infty\frac{2y}{y^2+3}\,dy\\)
    converge or diverge?
    If it converges, what is its value?
1.  Does \\(\int_e^\infty\frac{1}{\ln(x^x)}\,dx\\) converge or diverge?
    If it converges, what is its value?
1.  Show that
    \\(\int_1^\infty\frac{1}{x^2}\,dx+1=\int_0^1\frac{1}{\sqrt y}\,dy\\).
    Then draw a sketch involving areas illustrating why they are equal.
1.  Does \\(\sum_{n=0}^\infty\frac{2n}{n^2+3}\\) converge or diverge?
1.  Does \\(\sum_{n=3}^\infty\frac{4}{n(\ln n)^3}\\) converge or diverge?
1.  Does \\(\sum_{n=-2}^\infty\frac{1}{e^n}\\) converge or diverge?
1.  Show that
    \\(
      \int_1^\infty\frac{1}{x^2}\,dx
    \not=
      \sum_{n=1}^\infty\frac{1}{n^2}
    \\), even though they both converge.
1.  Does \\(\sum_{k=100}^\infty\frac{5}{\sqrt[7]{k^6}}\\) converge or diverge?
1.  Does \\(\sum_{n=5}^\infty\frac{1}{n^2-8n+16}\\) converge or diverge?
1.  (OPTIONAL) Does \\(\sum_{n=-1}^\infty\frac{e^n}{1+e^{2n}}\\) converge
    or diverge? (Hint: \\(\int\frac{1}{1+u^2}\,du=\tan^\leftarrow u+C\\)
    and \\(\lim_{u\to\infty}\tan^\leftarrow u=\frac{\pi}{2}\\).)
1.  (QUIZ)
    Does \\(\sum_{m=0}^\infty\frac{2m}{(m^2+1)^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It both converges and diverges.
1.  (QUIZ)
    Does \\(\sum_{n=2}^\infty\frac{1}{\sqrt{n-1}}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It neither converges nor diverges.

[Solutions 1-6]({{site.baseurl}}public/solutions/5.4a.pdf)

[Solutions 7-13]({{site.baseurl}}public/solutions/5.4b.pdf)

---

## 5.5 Comparison Tests

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.4

### 5.5.1 Direct Comparison Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/5DYYL4GlBuw" frameborder="0" allowfullscreen></iframe><!-- TODO rerecord -->

- Suppose \\(\sum_{n=N}^\infty a_n\\) is a series with non-negative terms.
    - If there exists a convergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where \\(a_n\leq b_n\\) for sufficiently
      large \\(n\\), then \\(\sum_{n=N}^\infty a_n\\) converges as well.
    - If there exists a divergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where \\(a_n\geq b_n\\) for sufficiently
      large \\(n\\), then \\(\sum_{n=N}^\infty a_n\\) diverges as well.
- **Example**
  Show that \\(\sum_{n=0}^\infty\frac{n}{n^3+3n+2}\\) converges by
  comparing with the series \\(\sum_{n=1}^\infty\frac{1}{n^2}\\).
- Following is a list of sequence formulas ordered from larger to
  smaller (for sufficiently large \\(n\\)).
    - \\(n^n\\)
    - \\(n!\\)
    - \\(b^n\\) where \\(b>1\\) (such as \\(2^n,e^n,10^n\\)...)
    - \\(n^p\\) where \\(p>0\\) (such as \\(\sqrt{n},n,n^4\\)...)
    - \\(\log_b n\\) where \\(b>1\\)
      (such as \\(\log_{10}(n),\ln(n),\log_2(n)\\)...)
    - any positive constant
- **Example**
  Does \\(\sum_{n=1}^\infty\frac{2}{n^{1/3}+5}\\) converge or diverge?
- **Example**
  Does \\(\sum_{k=3}^\infty\frac{3^n}{n!}\\) converge or diverge?
- **Example**
  Does \\(\sum_{m=2}^\infty(m\ln m)^{-1/2}\\) converge or diverge?


### 5.5.2 Limit Comparison Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ug9mAWcbwp0" frameborder="0" allowfullscreen></iframe><!-- TODO rerecord, consider just 0<lim<infty -->

- Suppose \\(\sum_{n=N}^\infty a_n\\) is a series with non-negative terms.
    - If there exists a convergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where
      \\(\lim_{n\to\infty}\frac{a_n}{b_n}<\infty\\),
      then \\(\sum_{n=N}^\infty a_n\\) converges as well.
    - If there exists a divergent series \\(\sum_{n=M}^\infty b_n\\)
      with non-negative terms where
      \\(\lim_{n\to\infty}\frac{a_n}{b_n}>0\\) (including divergence
      to infinity),
      then \\(\sum_{n=N}^\infty a_n\\) diverges as well.
- **Example**
  Does \\(\sum_{n=1}^\infty\frac{2}{n^{1/3}+5}\\) converge or diverge?
- **Example**
  Does \\(\sum_{i=0}^\infty\frac{3i}{5^i}\\) converge or diverge?
- **Example**
  Does \\(\sum_{n=42}^\infty\frac{2^n+5^n}{3^n+4^n}\\) converge or diverge?

### Exercises for 5.5

1.  Does \\(\sum_{n=0}^\infty\sqrt{\frac{n}{n^4+7}}\\) converge or
    diverge? (Use Direct Comparison.)
1.  Does \\(\sum_{n=3}^\infty\frac{4}{n^{0.8}-1}\\) converge or
    diverge? (Use Direct Comparison.)
1.  Does \\(\sum_{j=2}^\infty\frac{e^j}{e^{2j}+1}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{k=10}^\infty\frac{\sin^2(k)}{k^3}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{m=4}^\infty\frac{1}{\ln m}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{n=4}^\infty\frac{5}{2n+3}\\) converge or diverge?
    (Use Direct Comparison.)
1.  Does \\(\sum_{n=0}^\infty\sqrt{\frac{n}{n^4+7}}\\) converge or
    diverge? (Use Limit Comparison.)
1.  Does \\(\sum_{n=3}^\infty\frac{4}{n^{0.8}-1}\\) converge or
    diverge? (Use Limit Comparison.)
1.  Does \\(\sum_{j=2}^\infty\frac{e^j}{e^{2j}+1}\\) converge or diverge?
    (Use Limit Comparison.)
1.  Does \\(\sum_{k=10}^\infty\frac{\sin^2(k)}{k^3}\\) converge or diverge?
    (Use Limit Comparison.)
1.  Does \\(\sum_{m=4}^\infty\frac{1}{\ln m}\\) converge or diverge?
    (Use Limit Comparison.)
1.  Does \\(\sum_{n=4}^\infty\frac{5}{2n+3}\\) converge or diverge?
    (Use Limit Comparison.)
1.  (OPTIONAL)
    Does \\(\sum_{m=1}^\infty\frac{1}{1+2+\dots+(m-1)+m}\\) converge or diverge?
    (Hint: show that \\(
      \frac{1}{1+2+\dots+(m-1)+m}
        =
      \frac{2}{(1+m)+(2+m-1)+\dots+(m-1+2)+(m+1)}
    \\).)
1.  (QUIZ)
    Does \\(\sum_{m=0}^\infty\frac{2m}{(m^2+1)^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It both converges and diverges.
1.  (QUIZ) <!-- TODO add as actual exercise -->
    Does \\(\sum_{n=1}^\infty\sqrt{\frac{n+1}{n^2+3}}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It neither converges nor diverges.

[Solutions 1-8]({{site.baseurl}}public/solutions/5.5a.pdf)

[Solutions 9-15]({{site.baseurl}}public/solutions/5.5b.pdf)


---

## 5.6 Absolute and Conditional Convergence

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.5, 9.6

### 5.6.1 Absolute and Conditional Convergence

<iframe width="560" height="315" src="https://www.youtube.com/embed/SAmrF-Ac8o4" frameborder="0" allowfullscreen></iframe><!-- TODO rerecord -->


- A series \\(\sum_{n=N}^\infty a_n\\) absolutely converges whenever
  its absolute value series \\(\sum_{n=N}^\infty \|a_n\|\\) converges.
  All absolutely convergent series converge normally.
- **Example** Show that \\(\sum_{n=3}^\infty\frac{\cos n}{n^2}\\) absolutely
  converges.<!-- remove cos n -->
- **Example** Show that \\(\sum_{m=1}^\infty\frac{3^m}{(-4)^{m+1}}\\)
  absolutely converges.
- A convergent series which is not absolutely convergent is called
  conditionally convergent.
- Conditionally convergent series are named as such
  because the value of a conditionally
  convergent series depends on the order of its terms.

### 5.6.2 Alternating Series Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/qHhyQK0rPQ4" frameborder="0" allowfullscreen></iframe><!-- TODO rerecord -->


- The Alternating Series Test: let \\(\sum_{n=N}^\infty(-1)^n a_n\\)
  be a series such that \\(\\<a_n\\>\_{n=N}^\infty\\) has positive
  nonincreasing terms. Then \\(\sum_{n=N}^\infty(-1)^n a_n\\)
  converges when \\(\lim_{n\to\infty} a_n = 0\\).
- Also holds for \\(\sum_{n=N}^\infty(-1)^{n\pm k} a_n\\)
- **Example** Show that the alternating harmonic series
  \\(\sum_{n=1}^\infty\frac{(-1)^{n+1}}{n}\\) is conditionally convergent.
- **Example** Is the series
  \\(\sum_{k=3}^\infty\frac{\sin k}{k^2}\\) absolutely convergent,
  conditionally convergent, or divergent?
- Let \\(a_n\geq0\\). Then the sequence
  \\(\\<(-1)^na_n\\>\_{n=N}^\infty\\) converges if and only if
  \\(\\<a_n\\>\_{n=N}^\infty\\) converges to zero.
- **Example** Is the series
  \\(\sum_{n=0}^\infty\frac{(-e)^n}{n+1}\\) absolutely convergent,
  conditionally convergent, or divergent?
- **Example** Is the series
  \\(\sum_{m=2}^\infty(-1)^m\frac{m}{m^{3/2} +3}\\) absolutely convergent,
  conditionally convergent, or divergent?

### Exercises for 5.6

1.  Is the series
    \\(\sum_{m=2}^\infty\frac{3}{1-m^2}\\) absolutely convergent,
    conditionally convergent, or divergent?
1.  Is the series
    \\(\sum_{k=1}^\infty\frac{\cos^5 k}{k^4}\\) absolutely convergent,
    conditionally convergent, or divergent?
1.  Is the series
    \\(\sum_{n=0}^\infty(-1)^{n+1}\frac{4}{n^2+3}\\) absolutely convergent,
    conditionally convergent, or divergent?
1.  Is the series
    \\(\sum_{i=6}^\infty(-1)^i\frac{i}{\sqrt{i^3-7}}\\) absolutely convergent,
    conditionally convergent, or divergent?
1.  Is the series
    \\(\sum_{m=2}^\infty(-\frac{3}{5})^m\\) absolutely convergent,
    conditionally convergent, or divergent?
1.  Is the series
    \\(\sum_{m=2}^\infty(-\frac{5}{3})^m\\) absolutely convergent,
    conditionally convergent, or divergent?
1.  Is the series
    \\(\sum_{n=13}^\infty(-1)^n\frac{1}{n\ln n}\\) absolutely convergent,
    conditionally convergent, or divergent?<!-- TODO make (-1)^{n+1} -->

[Solutions]({{site.baseurl}}public/solutions/5.6.pdf)


---

## 5.7 Ratio and Root Tests

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.5 <!-- TODO consider putting before 5.6 -->

### 5.7.1 Ratio Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/gYkp0LuVi5g" frameborder="0" allowfullscreen></iframe>

- The Ratio Test states that the series \\(\sum_{n=N}^\infty a_n\\)
  absolutely converges when \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|<1\\)
  and diverges when \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|>1\\).
- **Example**
  Show that \\(\sum_{n=0}^\infty\frac{3^n+1}{4^n}\\) absolutely converges
  using the Ratio Test. Then give its value.
- **Example**
  Does \\(\sum_{k=3}^\infty\frac{(2k)!}{3(k!)^2}\\) converge or diverge?
- Another test must be used when
  \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|=1\\).
- **Example**
  Show that the divergent series
  \\(\sum_{n=1}^\infty\frac{1}{n}\\) and the absolutely convergent series
  \\(\sum_{n=1}^\infty\frac{1}{n^2}\\) both satisfy
  \\(\lim_{n\to\infty}\|\frac{a_{n+1}}{a_n}\|=1\\).

### 5.7.2 Root Test

<iframe width="560" height="315" src="https://www.youtube.com/embed/gMnZOesL3wY" frameborder="0" allowfullscreen></iframe>

- The Root Test states that the series \\(\sum_{n=N}^\infty a_n\\)
  absolutely converges when \\(\lim_{n\to\infty}\sqrt[n]{\|a_n\|}<1\\)
  and diverges when \\(\lim_{n\to\infty}\sqrt[n]{\|a_n\|}>1\\).
- **Example**
  Show that \\(\sum_{n=0}^\infty\frac{5^n}{2^{3n}}\\) absolutely converges
  using the Root Test. Then give its value.
- **Example**
  Does \\(\sum_{m=3}^\infty\frac{m^{10}}{(-3)^m}\\) converge or diverge?
- Another test must be used when
  \\(\lim_{n\to\infty}\sqrt[n]{\|a_n\|}=1\\).

### Exercises for 5.7

1.  Does \\(\sum_{k=1}^\infty\frac{k^2+4}{(k+2)!}\\) converge or diverge?
1.  Does \\(\sum_{n=0}^\infty\frac{(2n)!}{n+3}\\) converge or diverge?
1.  Does \\(\sum_{m=2}^\infty\frac{5^m}{m!}\\) converge or diverge?
1.  Does \\(\sum_{n=0}^\infty(-1)^n\frac{n!}{2^n(n+2)!}\\) converge or diverge?
1.  Does \\(\sum_{p=0}^\infty\frac{3^p}{(p+7)^p}\\) converge or diverge?
1.  Does \\(\sum_{n=9}^\infty(1+\frac{2}{n})^{n^2}\\) converge or diverge?
    (Hint: \\(e^x=\lim_{n\to\infty}(1+\frac{x}{n})^n\\).)
1.  Does \\(\sum_{j=3}^\infty(-3)^j\frac{1}{j4^j}\\) converge or diverge?
1.  Does \\(\sum_{n=1}^\infty\left(\frac{1-4n^2}{(n+1)(3n+1)}\right)^{n+3}\\)
    converge or diverge?
1.  (OPTIONAL)
    Does \\(\sum_{m=4}^\infty(-1)^{m+1}\frac{me^{-m}}{(2m+1)\ln(m+1)}\\)
    converge or diverge?
1.  (QUIZ)
    Does \\(\sum_{n=1}^\infty\frac{(n-1)!}{10^n}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It explodes.
1.  (QUIZ)
    Does \\(\sum_{k=3}^\infty(1-\frac{1}{k})^{k^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It converges some of the time, and diverges the rest of the time.
1.  (QUIZ)
    Does \\(\sum_{m=2}^\infty\frac{1}{m^2}\\) converge or
    diverge?
    - It converges.
    - It diverges.
    - It is impossible to determine.

[Solutions]({{site.baseurl}}public/solutions/5.7.pdf)