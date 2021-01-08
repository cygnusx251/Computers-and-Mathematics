<h1>Computers and Mathematics</h1>
<h5>Saptarshi Dandapat</h5>
<h5>Ramakrishna Mission Vidyamandira</h5>
<h5>Undergraduate Second Year</h5>
<h3>Theorem Proofs and Computer Programs</h3>
<p>Mathematicians rely on computer code to do all sorts of tedious calculations which would be unfeasible to do
by hand. But, what is a computer program? It is just is a sequence of statements following a precise syntax,
which performs a certain task when the statements are interpreted within the framework of a particular
programming language.</p>
<p>A mathematical proof is also a sequence of statements following precise syntax, which performs a cer-
tain task when the statements are interpreted within the logic and language of pure mathematics. This
observation is more than an analogy an goes back to Kolmogorov.</p>
<p>Now, in a computer program, bugs in code can cause chaos, allowing hackers into systems or stops stuffs
working. Hence, software developers have made tools which can check computer programs for bugs (like
Valgrind, other fuzzing softwares). As a consequence, the tools developed by computer scientists to verify
that code has no bugs can also be used to show that a proof in ”constructive” mathematics has no gaps or
errors. </p>
<p>However, one difference between proofs in pure mathematics and a computer program is that proofs are
allowed to use non-constructive things such as the axiom of choice, (which is, a function with no algorithm,
or no program). But some of the newer computer proof checking tools (such as Lean) have been designed
with mathematics in mind. and have simply added things like the axiom of choice as an axiom of the system.
This means, tools like lean, can now check normal mathematical proofs.</p>
<h3>Lean and formalising mathematics</h3>
<p><a href = "https://leanprover.github.io/">Lean</a> is an open source interactive theorem prover and functional programming language being developed at
Microsoft Research, hosted on GitHub. It aims to bridge the gap between interactive and automatic theorem
proving, by situating automated tools and methods in a framework that supports user interaction and the
construction of fully specified axiomatic proofs.</p>
<p>Lean has gotten attention from mathematicians <a href = "https://en.wikipedia.org/wiki/Thomas_Callister_Hales">Thomas Hales</a> and <a href = "https://en.wikipedia.org/wiki/Kevin_Buzzard">Kevin Buzzard</a>. One of the project by
Buzzard, the <a href="https://xenaproject.wordpress.com/what-is-the-xena-project/">Xena project</a> goals to rewrite every theorem and proof in the undergraduate math curriculam
of Imperial College London in Lean.</p>
<p>Hale’s 2017 <a href="https://www.newton.ac.uk/seminar/20170710100011001">talk</a> at the Big Proof workshop at the Isaac Newton Institute is available online. Here he
tells an interesting story of how he ended up having to formalize the paper proof which he and Ferguson had
constructed in the late 1990s. The argument involved, at some point, checking thousands and thousands of
nonlinear inequalities, and the human referees had expressed concern that this part of the argument was not
human-checkable. They have now all been formally verified by computer.</p>
<h3>What Lean can do</h3>
<p>Lean is a computer program which can</p>
<ol>
<li>Understand mathematical definitions and true/false statements.</li> 
<li>Check human proofs and theorems.</li>
<li>Try and find proofs on its own.</li>
</ol>
<h3>Achievable goals by Lean (now)</h3>
<ol>
<li>Puzzle games like the <a href="http://wwwf.imperial.ac.uk/~buzzard/xena/natural_number_game/">Natural Number Game</a>, which is basically building natural numbers and deriving
its properties from peano’s axioms, and proving inequalities using Lean.</li>
<li>Educational interactive books, with ”no errors”. Using lean we can write theorems and proofs or
exercises of a book in an entire topic like Real Analysis or Algebra, which will have exactly zero errors,
as it will be checked by the program.</li>
<li>Educational software which teaches proofs.</li>
<li>Databases of theorems. Lean has a math library which contains several theorem on the topics of
pure mathematics like algebra, algebraic geometry, analysis, category theory, measure theory, number
theory etc..</li>
<li>Intelligent Computer search through those databases. So, once we have databases we can search
theorems out of it. Whereas normal search in Google or anything is useless for searching a mathematical
theorem or proof.</li>
</ol>
<h3>What we can do in this colloquium</h3>
<ol>
<li>Learn how to state a theorem/conjecture in Lean.</li>
<li>Make mathematical definition in Lean.</li>
</ol>
<p>Then we can do a few examples of what we can do in Lean. Like some of our First year course, as proving
: There is a bijection between equivalence relations on X and partitions of X, in Algebra, or, proving some
basic properties of Natural numbers and complex numbers, in Analysis, or maybe some very basic concepts
of topology like, A set is closed if its complement is open and A function between topological spaces is
continuous if the preimage of every open set is open.</p>
<h3>How can it help in our curriculum</h3>
<p>Since, lean is a computer program, one can not reach the goal of proving a theorem by missing some steps.
Therefore practicing lean can help in our proof writing in pen and paper. We can become well acquainted
with the process of writing a proof from the existing axioms or given data. It will help us to learn what a
”proof” in mathematics really is, and how it is different from intuitive proofs often done in schools.</p>
<h3>External links and References</h3>
<ol>
<li><a href="https://leanprover.github.io/reference/">The Lean Reference Manual</a></li>
<li><a href="https://leanprover.github.io/theorem_proving_in_lean/">Theorem Proving in Lean</a></li>
<li><a href="http://wwwf.imperial.ac.uk/~buzzard/xena/natural_number_game/">The Natural Number Game</a> by Kevin Buzzard and Mohammad Pedramfar.</li>
<li><a href="https://github.com/blanchette/logical_verification_2020/raw/master/hitchhikers_guide.pdf">The Hitchhiker's guide to logical verification</a></li>
</ol>
