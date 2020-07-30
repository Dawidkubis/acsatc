<!DOCTYPE html> 
<html lang='en-US' xml:lang='en-US'> 
<head><title></title> 
<meta charset='utf-8' /> 
<meta content='TeX4ht (https://tug.org/tex4ht/)' name='generator' /> 
<meta content='width=device-width,initial-scale=1' name='viewport' /> 
<link href='introtext.css' rel='stylesheet' type='text/css' /> 
<meta content='introtext.tex' name='src' /> 
 <script async='async' id='MathJax-script' type='text/javascript' src='https://cdn.jsdelivr.net/npm/mathjax@3/es5/mml-chtml.js'></script>  
</head><body>
  <div id='colorbox1' class='colorbox'>Our goal is to study the complexity of convergence schemes and their limits. Sequences
(viewed as evolutions) with the absorption property lead to so-called <span class='cmti-10x-x-109'>generic objects</span>. One
of our objectives is to extend this study in several directions. We are also going to analyze
convergence schemes in which there are no evolutions with the absorption property, where
the set-theoretic forcing plays a pivotal role.                                                              </div>
  <h3 class='sectionHead'><a id='x1-1000'></a>Introduction</h3>
<!-- l. 450 --><p class='noindent'>Let us imagine that a certain evolution system is given, starting from some initial state
<!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msub><mrow><mi>E</mi></mrow><mrow><mn>0</mn></mrow></msub></math> and having the property that
for every two transitions <!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>f</mi></math>,
<!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>g</mi></math> from the same state
<!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>Z</mi></math> it is possible to make
two further transitions <!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msup><mrow><mi>f</mi></mrow><mrow><mi>′</mi></mrow></msup></math>,
<!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msup><mrow><mi>g</mi></mrow><mrow><mi>′</mi></mrow></msup></math> so that the
compositions <!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msup><mrow><mi>f</mi></mrow><mrow><mi>′</mi></mrow></msup><mi>f</mi></math>
and <!-- l. 450 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msup><mrow><mi>g</mi></mrow><mrow><mi>′</mi></mrow></msup><mi>g</mi></math> are the
same, in particular, leading to the same state. It is then natural to expect that there exists a special infinite process
accumulating all possible states and in some sense absorbing all possible transitions. Specifically, denoting a fixed
transition <!-- l. 451 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>f</mi></math>
from <!-- l. 451 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>A</mi></math> to
<!-- l. 451 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>B</mi></math> by
<!-- l. 451 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>A</mi><mover class='stackrel'><mrow><mo class='MathClass-rel'>→</mo></mrow><mrow><mrow><mi>f</mi></mrow></mrow></mover><mi>B</mi></math>, an
infinite process (evolution) can be represented as an infinite diagram of the form
<!-- tex4ht:inline --></p><!-- l. 452 --><math display='block' xmlns='http://www.w3.org/1998/Math/MathML'>
                              <object height='28.24263 ' data='introtext-1.svg' type='image/svg+xml' width='216.6024 '><p>SVG-Viewer needed.</p></object>
</math>
<!-- l. 454 --><p class='nopar'> where <!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msub><mrow><mi>A</mi></mrow><mrow><mn>0</mn></mrow></msub> <mo class='MathClass-rel'>=</mo> <msub><mrow><mi>E</mi></mrow><mrow><mn>0</mn></mrow></msub></math>.
Saying that such a process <tspan font-family='cmti' font-size='10'>absorbs </tspan>all possible transitions means that for every
<!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>n</mi></math>, given a transition
<!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msub><mrow><mi>A</mi></mrow><mrow><mi>n</mi></mrow></msub><mover class='stackrel'><mrow><mo class='MathClass-rel'>→</mo></mrow><mrow><mrow><mi>f</mi></mrow></mrow></mover><mi>Y</mi> </math>, there exist
<!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>m</mi> <mo class='MathClass-rel'>&gt;</mo> <mi>n</mi></math> and a transition
<!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>Y</mi> <mover class='stackrel'><mrow><mo class='MathClass-rel'>→</mo></mrow><mrow><mrow><mi>g</mi></mrow></mrow></mover><msub><mrow><mi>A</mi></mrow><mrow><mi>m</mi></mrow></msub></math> such that the
composite transition <!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><msub><mrow><mi>f</mi></mrow><mrow><mi>m</mi><mo class='MathClass-bin'>−</mo><mn>1</mn></mrow></msub><mi class='MathClass-op'>…</mi><mo> ⁡<!-- FUNCTION APPLICATION --></mo><msub><mrow><mi>f</mi></mrow><mrow><mi>n</mi></mrow></msub></math>
is the same as <!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>gf</mi></math> or at
least approximates <!-- l. 455 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>gf</mi></math>
with a given in advance error. It turns out that if a process with the absorption property exists, it is
essentially unique and may be called <tspan font-family='cmti' font-size='10'>generic</tspan>. This means that every two processes with the absorption
property are isomorphic, which in turn means that there is a way of “jumping” between the first and the
                                                                                            
                                                                                            
second one infinitely many times.
</p><!-- l. 458 --><p class='indent'>It is rather evident that the proper framework for describing and studying such evolution systems comes
from category theory. Namely, the objects are the system states while the arrows are transitions.
Category theory offers here elegant and quite strong, yet at the same time manageable, tools to be
utilized. Perhaps one of the basics is the concept of a functor. In order to describe an infinite
transition process (evolution), it suffices to use functors from the set of non-negative integers
<!-- l. 458 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>ω</mi></math> (more traditionally
denoted by <!-- l. 458 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>ℕ</mi></math>)
viewed as a category in which the objects are natural numbers and arrows are pairs of the form
<!-- l. 458 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mrow><mo class='MathClass-open'>⟨</mo><mrow><mi>n</mi><mo class='MathClass-punc'>,</mo> <mi>m</mi></mrow><mo class='MathClass-close'>⟩</mo></mrow></math> with
<!-- l. 458 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>n</mi> <mo class='MathClass-rel'>≤</mo> <mi>m</mi></math>.
</p><!-- l. 460 --><p class='indent'>Actually, a significant power of category theory lies within the notion of <tspan font-family='cmti' font-size='10'>colimit </tspan>of a functor, unifying
concepts like <tspan font-family='cmti' font-size='10'>supremum </tspan>in partially ordered sets, Cartesian products, unions of families of structures, and so
on. In particular, every functor from the natural numbers has its colimit in a suitable, possibly bigger,
category.
</p><!-- l. 462 --><p class='indent'>While it is possible to investigate evolution processes in their “pure” form, it is usually more convenient
and more natural to look at their colimits, identifying them with the isomorphism classes of certain objects
of a bigger category.
</p><!-- l. 464 --><p class='indent'>In this way we arrive at the basic concept of this project: abstract convergence scheme, namely a category
<!-- l. 464 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math> embedded into a
category <!-- l. 464 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi></math> consisting of
limits of sequences from <!-- l. 464 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math>.
Here, the “limit” may be either as “colimit” in the category-theoretic sense or some more general operator
acting on <tspan font-family='cmti' font-size='10'>certain </tspan>sequences, possessing the main properties of colimits.
</p>
<h3 class='sectionHead'><a id='x1-2000'></a>Abstract convergence schemes</h3>
<!-- l. 472 --><p class='noindent'>By an <tspan font-family='cmti' font-size='10'>abstract convergence scheme  </tspan>we mean a triple
<!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mrow><mo class='MathClass-open'>(</mo><mrow><mi>𝔎</mi><mo class='MathClass-punc'>,</mo> <mi mathvariant='italic'>σ𝔎</mi><mo class='MathClass-punc'>,</mo><mi class='qopname'> lim</mi><mo> ⁡<!-- FUNCTION APPLICATION --> </mo></mrow><mo class='MathClass-close'>)</mo></mrow></math>, where
<!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math> is a category,
<!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi> <mo class='MathClass-rel'>⊇</mo> <mi>𝔎</mi></math> is a bigger category,
<!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi class='qopname'>lim</mi><mo> ⁡<!-- FUNCTION APPLICATION --> </mo></math> is an operator assigning
to some sequences in <!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math>
(or, more generally, covariant functors from some directed posets into
<!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math>) their
co-cones in <!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi></math>,
pretending to be their colimits. There is a short list of natural axioms (in the spirit of Hausdorff
convergence of sequences of points) making this structure sound and meaningful. In most cases,
<!-- l. 472 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi class='qopname'>lim</mi><mo> ⁡<!-- FUNCTION APPLICATION --> </mo></math> is the
colimit in the category-theoretic sense. An example of a convergence scheme may be a partially ordered set
<!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>P</mi></math>, with
<!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σP</mi></math>
being the set of all ideals generated by increasing sequences in
<!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>P</mi></math> (we identify
<!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>p</mi> <mo class='MathClass-rel'>∈</mo> <mi>P</mi></math> with the ideal
generated by <!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>p</mi></math>). Then
<!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi class='qopname'>lim</mi><mo> ⁡<!-- FUNCTION APPLICATION --> </mo><mrow><mo class='MathClass-open'>(</mo><mrow><msub><mrow><mi>x</mi></mrow><mrow><mi>n</mi> </mrow> </msub> </mrow><mo class='MathClass-close'>)</mo></mrow></math> is simply the ideal generated by the
sequence <!-- l. 473 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mrow><mo class='MathClass-open'>(</mo><mrow><msub><mrow><mi>x</mi></mrow><mrow><mi>n</mi></mrow></msub></mrow><mo class='MathClass-close'>)</mo></mrow></math>. Many natural examples
come from model theory, where <!-- l. 474 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math>
                                                                                            
                                                                                            
is a category of finite (or finitely generated) models of a fixed first-order language with embeddings as arrows,
while <!-- l. 474 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi></math>
is the category of all models isomorphic to unions of countable chains in
<!-- l. 474 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi>𝔎</mi></math>, again with embeddings as arrows.
Now <!-- l. 475 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi class='qopname'> lim</mi><mo> ⁡<!-- FUNCTION APPLICATION --> </mo> <mrow><mo class='MathClass-open'>(</mo><mrow><msub><mrow><mi>x</mi></mrow><mrow><mi>n</mi></mrow></msub></mrow><mo class='MathClass-close'>)</mo></mrow></math> is isomorphic to the union
(formally: colimit) of the chain <!-- l. 475 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mrow><mo class='MathClass-open'>(</mo><mrow><msub><mrow><mi>x</mi></mrow><mrow><mi>n</mi></mrow></msub></mrow><mo class='MathClass-close'>)</mo></mrow></math>,
as embeddings can always be replaced by inclusions).
</p><!-- l. 477 --><p class='indent'>Given a concrete convergence scheme, one has to first consider whether any interesting
<!-- l. 477 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi></math>-object
occurs as the “limit”. If so, then there is a chance that, up to isomorphism, a “special’ object occurs “most
frequently”. Of course, this needs to be made precise, either by finding a reasonable topology on the objects
of <!-- l. 478 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi></math>,
where “occurring frequently” means forming a non-meager or even a co-meager
set. Another option is to find a reasonable probability measure on the objects of
<!-- l. 479 --><math display='inline' xmlns='http://www.w3.org/1998/Math/MathML'><mi mathvariant='italic'>σ𝔎</mi></math>, where
“occurring frequently” would mean “with positive probability” or even “with probability one”. A more
abstract approach would require considering some ideal of “small” sets whose complements are therefore
called “large”. Actually, a quite common word for “occurring most frequently” or “typically” is “being
generic”. This name has been used in the theory of set-theoretic forcing (generic filters) and
from time to time is used in descriptive set theory, when considering a complete topological
space whose elements could have various properties. Thanks to the Baire category theorem, we
can say that a fixed property is <tspan font-family='cmti' font-size='10'>generic </tspan>if elements without this property form a meager set.
In the project we are going to explore the concept of being generic in abstract convergence
schemes.
</p>
 
</body> 
</html>
