Design and Analysis of Computer Algorithms - with Professor Kostas Bekris
=========================================================================

Syllabus
--------

### Topics

We will cover a large subset of the following and possibly some new
algorithmic topics and applications, as time permits:

-   Mathematical tools. Review of mathematical background, concepts of
    algorithm design, complexity, asymptotics, induction, and
    randomization. Fibonacci numbers. Euclidean gcd algorithms.
    Universal hashing.

-   Divide and conquer. Fast integer multiplication; recurrences; the
    master theorem; mergesort; randomized median and selection
    algorithms; quicksort; fast matrix multiplication.

-   Sorting. Lower bounds for comparison-based sorting; binsort and
    radix sort.

-   Dynamic programming; Paradigm of SPs in DAGs; longest increasing
    subsequence; approximate string matching; integer and (0,1) knapsack
    problems; chain matrix multiplication; single-pair reliable SPs,
    all-pairs SPs; independent sets.

-   Graph search. Graph classes and representations; depth first search
    in undirected and directed graphs; topological search; strongly
    connected components. Breadth first search and layered DAGs.

-   Shortest Paths (SPs) in digraphs. Single-source SPs for nonnegative
    edge weights; priority queues and Dijkstra; SPs in DAGs;
    single-source SPs for general edge weights. Maximum adjacency
    search.

-   Greedy algorithms. Spanning trees and cuts, analysis of union-find
    and path compression; MST algorithms; randomized algorithm for
    global minimum cuts; approximate set cover.

-   Network flows. Max flow min cut theorem and integrality; fast
    algorithms; disjoint (s,t)-dipaths; maximum bipartite matching &
    minimum vertex cover. Global minimum cuts.

-   Elements of NP-completeness & problem reductions.
-   NP-hard problems. Search and selected approximation algorithms.

### Prerequisites

Courses:

-   CS 112 Data Structures
-   CS 206 Introduction to Discrete Structures II

We assume (and briefly review early on in the class) elements of
discrete mathematics, such as logarithms, proofs by induction, series
and sums, permutations, asymptotics (big-Oh, big-Omega notation), basics
of solving recurrences, as well as concepts of programming and data
structures, e.g., linked lists, stacks, queues, trees, binary search,
recursion, hashing, priority queues, graph algorithms, sorting.

### Reading Material

The class will primarily draw upon material from the following book:

-   "Algorithms" by Dasgupta, Papadimitriou & Vazirani, McGraw Hill,
    2008.

The following book may also be used as reference:

-   "Introduction to Algorithms" by Cormen, Leiserson, Rivest & Stein,
    McGraw Hill (The chapters in the calendar below refer to the 2nd
    edition)

The books are not required for the class. Students are expected to take
notes during the presentation of the material in the classroom and the
recitations. Homeworks and exams will be based on the presented
material.

### Exams

There will be three exams: two midterms and one final. The first midterm
will cover the material of the first third of the course, and the second
midterm will cover the second third of the course. The final exam will
cover material from the entire class. Check the tentative schedule for
updates. All exams will be in-class on a date arranged and announced
ahead of time.

A missed exam draws zero credit. Emergencies will be considered upon
submitting a University-issued written verification to the Instructor;
for assistance contact your Dean's Office. Also, check the definition of
[Final Exam](http://sasundergrad.rutgers.edu/forms/final-exam-conflict)
by SAS.

### Homework Assignments

There will be 4 to 5 homeworks. You will be informed in advance when an
assignment is due. A tentative scheduled is available on the course's
website. The homeworks consist of practice questions which are intended
to assist students in mastering the course content. They may also
potentially involve limited programming effort.

Homeworks should be completed by teams of students - three at most. No
additional credit will be given for students that complete a homework
individually. Please inform Athanasios Krontiris about the members of
your team (email: tdk.krontir/AT/gmail.com).

Students will receive 10% extra credit if they typeset their report
using LaTeX or 5\\% extra credit if they typewrite their answers (e.g.,
using Word). Submit only PDF documents. For instance, if a pair was to
receive a score of 62/100 and they typeset their report, then their
score will be 68/100, i.e,. they receive a bonus of +10\\% of 62 points.
Resources on how to use LaTeX are available below.

### Submission Rules

No late submission is allowed. If you don't submit a homework on time,
you get 0 points for that homework. The deadline will typically
correspond to the beginning of a lecture. Students can submit their
homeworks electronically via Sakai.

### Grading System

The final grade will be computed according to the following rule
\*\*(this is tentative and can change)\*\*:

final grade = max(Case A: With Homeworks, Case B: Without Homeworks)

Case A: With Homeworks

-   Homeworks: 20 points total
-   First midterm: 25 points
-   Second midterm: 25 points
-   Final exam: 30 points
-   Participation: +/- 5 points (this is up to the discretion of the
    instructor and the TAs)

Case B: Without Homeworks

-   First midterm: 30 points
-   Second midterm: 30 points
-   Final exam: 40 points
-   Participation: +/- 5 points (this is up to the discretion of the
    instructor and the TAs)

On any assignment (homework or exam), you can either attempt to answer
the question, in which case you will receive between 0 and 100% credit
for that question, or you can write "I don't know", in which case you
receive 25% credit for that question. Leaving the question blank is the
same as writing "I don't know." You can and will get less than 25%
credit for a question that you answer erroneously.

Finally, the first exam is a make-or-break situation. If your score on
the first exam is 26% or less (which amounts to a blank exam) then you
fail the class. The first exam will be early enough for you to drop the
class.

Your participation grade can be positive or negative. By default your
participation grade is 0..., e.g., if you typically come to the
lectures/recitations but you rarely answer questions during the lectures
or the recitations, your participation grade will be 0. Positive
participation grades will be given to students that actively participate
in lectures and recitations. You can also receive a negative
participation grade depending on the level of your involvement in the
course lectures and recitations (or lack there of) or because of issues
related to collusion or cheating in homeworks and exams.

The mapping of scores to letter grades will be determined at the end of
the semester. As a **rough** guide, the following rule may be used for
the final grade \*\*(it will be adapted close to the end of the
semester)\*\*:

-   A: \> 89
-   B+: 80-89
-   B: 70-79
-   C+: 60-69
-   C: 50-59
-   D: 40-49
-   F: less than 40

Students interested in a recommendation letter by the instructor will be
offered one only if they achieve a score above 95 after the completion
of the course.

### Questions about Grading

If you have a question or complaint regarding the points you received on
specific parts of a HW assignment, or an exam, staple a sheet of paper
on the graded item, stating specifically but very briefly what parts of
that document you wish to have reviewed and forward it to Athanasios
Krontiris, who will handle the process of communicating with the
instructor and the other TAs. Please refrain from verbal arguments about
grades with the instructor or with any of the TAs. We will try to get
back to you within two weeks. The deadline for submitting such requests
is the last lecture.

### Academic Standards

Exams are to be treated as individual efforts. Homeworks are not to be
treated as collective efforts beyond the participation of the team
members! Discussions are not allowed on how to solve specific questions
in homeworks. Do not discuss assignments with students that are not
currently taking the class.

A severe penalty will be given to any assignment which indicates
collusion or cheating. The usual penalty for cheating on an assignment
or an exam is failure in the course. At a minimum your participation
grade will be influenced negatively. Stealing another person's listing
or having another person "ghost write" an assignment will be considered
cheating.

Turning in work without properly citing the sources of the content
included in your work is plagiarism. All kinds of sources are included
in this definition, even those downloaded from the web, in which case an
operable link must be cited. Plagiarism from the web or other sources is
considered cheating and has the same effects. Even with a reference,
submitting an answer to a homework question, verbatim from any source
and without any contribution on your part, draws zero credit.

You should carefully study the website of Rutgers University on
[Academic Integrity](http://academicintegrity.rutgers.edu/) and the
corresponding
[policy](http://academicintegrity.rutgers.edu/policy-on-academic-integrity),
as well as the corresponding
[policy](http://www.cs.rutgers.edu/policies/academicintegrity/) from the
department of Computer Science. Your continued enrollment in this course
implies that you have read these policies, and that you subscribe to the
principles stated therein.

### LaTeX Resources

General info on what you can do with LaTeX: [Getting Started
with](http://www.maths.tcd.ie/%7Edwilkins/LaTeXPrimer/) [The Not So
Short Introduction
to](http://www.cse.unr.edu/robotics/bekris/cs482_f09/sites/cse.unr.edu.robotics.bekris.cs482_f09/files/lshort.pdf)
[Comprehensive List of
Latex](http://www.cse.unr.edu/robotics/bekris/cs482_f09/sites/cse.unr.edu.robotics.bekris.cs482_f09/files/comprehensive.pdf)
[Latex for Logicians](http://www.logicmatters.net/latex-for-logicians/)

Mac [Tex on Mac OS X](http://ii2.sourceforge.net/tex-index.html)
[MacTex](http://www.tug.org/mactex/)

The first link describes many alternatives that are available for
installing Tex on a Mac. The second link forwards to the MacTex package,
one of the alternatives mentioned in the first website. MaxTex provides
everythink that you need to use Latex on Mac except from a text editor.
It is, however, compatible with a wide variety of popular editors (e.g.,
Alpha, BBEdit, Emacs, VIM, iTeXMac, TeXShop). Note that MaxTex is a
large package.

Carbon Emacs has been succesfully tested with MacTex. After installing
MacTex, it is possible to directly compile and view \*.tex files from
Carbon Emacs's UI.

Note for Mac users: You will probably have problems previewing your PDF
output when using the postscript images provided by the instructor for
developing the notes. Nevertheless, the PDF file can be printed
properly. Prepare your document without the images and then add them.
You will probably still be able to preview the intermediate .dvi output
file with the "xdvi" program.

Linux (Ubuntu) [Latex on
Ubuntu](https://help.ubuntu.com/community/LaTeX) [Tex
Live](http://www.tug.org/texlive/)

You just have to download and install the proper packages described
above (e.g., through apt-get), use your favorite editor (e.g., emacs) to
prepare a \*.tex file and then you compile (run at least two times:
"latex filename.tex") to get the \*.dvi output. You can go from dvi to
postscript with the command "dvips" and you can convert postscript to
pdf with the command "ps2pdf".

Windows [Latex for Windows help](http://faculty.smu.edu/barr/latex/)
[MikTex (Latex for Windows)](http://miktex.org/)

If you follow the instructions on the first link you should be able to
get it working on a Windows system.

Below you can find Windows executables (32 bit) for the following
programs (follow the order when installing):

[MiKTeX](http://www.cse.unr.edu/robotics/bekris/cs482_f09/sites/cse.unr.edu.robotics.bekris.cs482_f09/files/setup-2.7.3092.exe)

[Ghostscript](http://www.cse.unr.edu/robotics/bekris/cs482_f09/sites/cse.unr.edu.robotics.bekris.cs482_f09/files/gs863w32.exe)

[Ghostview](http://www.cse.unr.edu/robotics/bekris/cs482_f09/sites/cse.unr.edu.robotics.bekris.cs482_f09/files/gsv49w32.exe)

[WinEdt](http://www.cse.unr.edu/robotics/bekris/cs482_f09/sites/cse.unr.edu.robotics.bekris.cs482_f09/files/winedt55.exe)

January 24th, 2014 - Lecture
----------------------------

### Fibonacci

-   He was an Italian mathematician in the 13th century who designed a
    famous sequence of numbers.

    $$ 0, 1, 2, 3, 5, 8, 13, ... $$

    -   We can design an algorithm to compute this.

        $$F_n = F_{n - 1} + F_{n - 2} $$

    -   And this can be expressed as a psuedocode function

            fib(n) {
                if (n == 0 | n == 1) {
                    return n;
                } else {
                    return fib(n - 1) + fib(n - 2)
                }
            }

    -   $T(n)$ grows at least as much as the value of $Fn$.

        $$ F_n \approx 2^{0.694n} $$

        -   This grows exponetially as a function of n.

-   If today, you can compute the 100th number, then after a year,
    hardware will allow you to computer the 101th number in a sequence.

-   A new function for Fibonacci:

        fib(n) {
            if (n <= 1) {
                return n;
            }

            int F[n];
            F[0] = 0;
            F[1] = 1;

            for (int i = 2; ; n++) {
                F[i] = F[i - 1] + F[1 - 2];

                return F[n];
            }
        }

-   Eventually, the cost is not exponetial, as now our function is
    linear, it's in the order of n.

-   Now, it's quite feasible to get to 200,000th number in the sequence.

### Computations

-   So far, all computations were treated as equal cost operations.
    -   This is a convinient simplication, but it is not true.
    -   For instance, addition.
        -   For numbers that can fit within your computer's register,
            say, 32-bits or 64-bits, then it takes only steps.

        -   But for big numbers like the Fibonacci numbers, like
            $0.69 / n$ bits.

-   Arithemetic operations on large numbers cannot be treated as a
    single step. You need to think about their representation.

    -   We need to think in terms of the representation of numbers.
        -   For example, a number *N* in base *b*.
        -   You need $\left \lceil{log_b (N+1) \right \rceil$ digits.

-   If cost of addition is linear to the size of bit representation,
    what is the cost of `fib(n)`?

### Running Time Simplification

-   If you have two functions that represent two running times for
    algorithms,

    $$f(n) = O(g(n))$$

    $$\exists c, n_0, f(n) \le c \times g(n) \forall n \ge n_0$$

January 29th, 2013 <small>Lecture</small>
-----------------------------------------

### Multiplication

-   Example: 13 times 11

            1101
            1011
            ----
            1101
           1101
          0000
         1101
         10001111

-   To compute each row, eitther "X" or "0", left-shifted.
    -    The rows are in the order of "2N"
    -    You have to sum them up, and you can do this pairwise.

-   If you do *n* times an operation which costs *n*, your runtime
    is going to be $n^2$.
    -   Multiplication is more expensive than addition.
    -   Multiplication is quadratic, where addition is linear (with
        respect to the size of the input).

### Alternative Multiplication

-   If you have two decimal numbers, *x* and *y*, write them next
    to each other.

        11           13
        5            26
        2   IGNORE   52
        1            104
        ----------------
                    143 (= 13 + 26 + 104)

-   Notice that the third row is ignored in both varieties of
    multiplication.

    $$ x \times y =\begin{cases} 2 (x \times \lfloor \frac{y}{2} \rfloor, & \text{if $y$ is even}.\\ x + 2(x \times \lfloor \frac{y}{2} \rfloor, & \text{if $y$ is odd}. \end{cases} $$


-   The expensive operation is the addition if $y$ is odd.
    So O(n) due to addition.
    -   Again, big-O is quadratic.

### Modula Arithmetic

$$ O(n) $$

### Modulo Multiplication

-   The product can be in the order of $(N - 1)^2$.
    -   The product will be at most *2N* bits long.

$$ O(n^2) $$

### Problems

Primality 

:   Given a number N, determine whether it is prime.

Factorning

:   Given a number N, express it as a product of prime
    numbers.

January 29th, 2014 <small>Recitation</small>
--------------------------------------------

### Asymptotic Bounds

-   There are three types we'll use
    1.  Tight bound
    2.  Lower bound
    3.  Upper bound, "big O"

#### Upper Bound (Big-O)

$$f(n) = O(g(n))$$

> G is upper upper bound for F if and only if there exists
> a constant and $n_0$ such that:
>
> $ 0 \le f(n) \le c g(n) $

**O(f) grows no faster than ..**

#### Lower Bound (Big Omega)

$$f(n) = \Omega(g(n))$$
$$\exists c, n_0 (0 \le c g(n) \le f(n) \forall n \ge n_o)$$

**O(f) grows faster than ...**

#### Tightly Bound (Big Theta)

**O(f) grows equal to**

### Runtimes

Name | Function
-----|---------
Logarithmic | *O(log(n))*
Constant | *O(n)*
Power | $O(n^a)$
Exponential | $O(a^n)$

January 31st, 2014 <small>Lecture</small>
-----------------------------------------

-   All cryptography is based on number theory and number
    theoretic properties.
    -   Think of message as modulo *N*.
    -   Longer message can be broken into smaller pieces.
    -   What is a good value for *N*?

### Property

-   Pick any two primes, and lets call them *p* and *q*.
    -   Then let *N* be their product, *N* = *p* \* *q*.
    -   For any *e* so that gcd(e, (p - 1)(q - 1)) = 1
    -   Then the following are true:
        1.  Take a number x and think of it as your message
            in your communication, then $x \to x^e$ is a 
            bijection.
            -   An a bijection is a one-to-one mapping.
        
        2.  Let $d = e^{-1} mod (p - 1)(q - 1)$, then,

            $$\forall x \in [0, N - 1] (x^e)^d \equiv x mod N$$

#### Example

-   Lets say our two prime numbers are p = 5, q = 11.
    -   Our N = pq = 55.
    -   Now we need to find e such that gcd(e, (5 - 1)(11 - 1)).
        -   So the GCD is 1.

    -   So lets pick e = 3 is sufficient??
        -   So what is the valye of d?

            $$d \equive e^{-1} mod (p - 1)(q - 1) \equive 3^{-1} mod 40 $$

    -   This means that 3 times d is equal to modulo 40, which is the
        modular inverse.
        -   For d = 27, we have 3 times 27 which equals 81 or modulo 40.

    -   For any message, x modula 55, ecryption is 

        $$ y = x^3 mod 55 $$

    -   For any message, decryption is

        $$ x = y^{27} mod 55 $$

### Proof of property

-   We have to show that

    $$(x^e)^d mod N \equiv x mod N $$

    -   The following are true if e and d have been selected
        as specific

        $$ e \times d \equiv 1 mod (p - 1)(q - 1) \equiv e \times d = k (p - 1)(q - 1) + 1 $$

> **Fermat's Little Theorem**: If *p* is prime, then
> $\forall 1 \le a \le p$:
> 
> $a^p \equive a mod p$
> $a^{p -1} \equiv 1 mod p$

### Summary of RSA

#### Bob

1.  Pick two prime numbers, this is the *p* and *q*
    -   And for the security of the system, pick two
        *large* primes.

2.  You announce to the world that everyone should be
    sending your message, that is, publish (N, e) where
    N equals p times q and e relative prime to
    (p - 1)(q - 1).
3.  Internally compute the private key, which is d equal
    the inverse of e module (p - 1)(q - 1).
    -   If you mulitply the two and modulo product, the value
        should be one.

#### Alice

1.  Generate encrypted message $x^e mod N$ where e and N come from
    Bob public key.
2.  When Bob receives this message $x = y^d mod N$.

### Why is this secure?

-   To break the system, Eve must be able to compute x that has
    never left Alice given the publically available information,
    and the public key (N, e).
    -   How do you do this?
        -   Try to guess x so that $y = x^e$

-   Alternatively, she can try to factor out p and q from N,
    hence, the intractable factoring problem.

### Analysis

> What are the operations of RSA and what is the running time?

-   Modular exponentiation, plus the decoding.
-   We have to select e, a small integer, but it has to be a relative
    prime
-   Compute $d = e^{-1} mod (p - 1)(q - 1)$ which always exists
    when $e$ is a relative prime.
-   Pick 2 large prime numbers.

#### Modular exponentiation



