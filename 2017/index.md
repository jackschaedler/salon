---
layout: default
title: Dialectics for new computer science
edition: 2017
theme: red
---
<header>
<div class="art-meta" id="art-meta"><div class="container">
  <div class="row">
    <div class="col-sm-12">
      <h1 class="sdr">Salon des Refusés 2017</h1>
      <h1>{{ page.title }}</h1>
    </div>
  </div>
  <div class="row"><div class="col-md-6">
    <p>Salon des Refusés ("exhibition of rejects") was an 1863 exhibition of artworks rejected from
    the official Paris Salon. It displayed works by later famous modernists such as Édouard Manet,
    whose paintings were rejected by the conservative jury of the Paris Salon. We feel that a similar space 
    is needed to explore new ideas and new ways of doing programming research and computer science.</p>

    <p>Many interesting ideas about programming struggle to find space in the modern programming 
    language research community, often because they are difficult to evaluate using proofs, 
    measurements or controlled user studies. As a result, new ideas are often seen as "unscientific".</p>
    
  </div><div class="col-md-6">
    <p>To provide space for unorthodox thought provoking ideas, we take inspiration from literary
    criticism. Papers that provoked an interesting discussion or criticism among the program committee 
    members were presented together with an attributed critical review that presents an alternative
    position, develops additional context or summarizes discussion about the work.</p>

    <p>In 2017, we accepted the 8 most inspiring papers out of 16 submissions. Below, you'll
    find the revised versions of the papers with critical commentary. We hope both will
    encou&shy;rage you to find new ways of doing and thinking about computer science!</p>
  </div></div>
  <div class="row"><div class="col-sm-12">
    <p class="links">
      <a href="#article"><i class="fa fa-arrow-circle-down"></i> Salon des Refusés 2017 papers</a>
    </p>          
  </div></div>
</div></div>

{% include header.html %}
</header>


<article id="article">
<section style="margin-top:0px">
<div class="container">
<div class="row"><div class="col-md-9" markdown="1">

## The nature of program code

Should we treat program code as a _text_ just like works of literature or as _blocks_ in 
visual programming languages? Does styling and formatting of program code let us express
something more about the program as in a stylized poem, or is it better to eliminate formatting
from our code altogether? The first two papers looks at different ways of thinking and
working with code. 

</div></div>
</div>
</section>

<div class="container outlines">
<div class="row"><div class="col-md-6" markdown="1">

### [Programming is writing is programming](/salon/2017/papers/writing-is-programming-is-writing/paper)

> **Authors**: Felienne Hermans, Marlies Aldewereld<br />
> **Critique**: Tomas Petricek

#### [Paper abstract](/salon/2017/papers/writing-is-programming-is-writing/paper)
Writing and programming are often seen as different: writing a creative profession, 
programming a technical one. Below the surface however, there is one striking similarity.
This paper compares writing and programming and uncovers similarities between some of the steps 
of writing and programming workflows. We also observe differences, like the attention that 
writers spent on formatting and styling, and the opportunity for feedback in programming.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

#### [Critique abstract](/salon/2017/papers/writing-is-programming-is-writing/critique)
The paper thus opens an interesting line of thought. What can we say by contrasting
programming with writing? At the surface, writing and programming are both about communicating 
an idea. Programming research often tries to distill such ideas to their core essence. Analogies 
with writing can help us understand the flaws and limitations of this approach. A summary of a 
novel on Wikipedia is not the same thing as the novel. Furthermore, writers often use styling 
and formatting to add a twist to an idea.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the critique (coming soon)</p>

</div>
<div class="col-md-6" markdown="1">


### [Code is not just text: Why our code editors are inadequate tools](/salon/2017/papers/code-is-not-just-text/paper)

> **Author**: Gregor Weber<br />
> **Critique**: Felienne Hermans

#### [Paper abstract](/salon/2017/papers/code-is-not-just-text/paper)
The most popular code editors treat code like any other form of text.
This leads to all kinds of problems, from syntax errors to code style 
inconsistencies. Alternative editors, namely visual programming languages, 
are available, but mostly in the form of educational tools and therefore 
have their own set of problems when used productively. But there might be 
a middle ground worth exploring, between the high productivity of traditional 
editors and the constrained interactivity of visual programming languages.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

#### [Critique abstract](/salon/2017/papers/code-is-not-just-text/critique)
This paper describes the current state of code editors, and how they could improve. I am 
super happy there is a paper about code editors, of course, since mu interest is in unconventional 
code editors, like Excel and Scratch. When reviewing this paper my attention is mostly drawn not 
to the described solution but to some of the assumptions the author is making. And that is not 
just because the solution is not there yet. There are some assumptions made in the paper that 
have not yet deserved enough attention.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the critique (coming soon)</p>

</div></div>
</div>

<section>
<div class="container">
<div class="row"><div class="col-md-9" markdown="1">

## Emerging ideas for building systems

What will software development of the future look like? The papers in this section look
at two novel trends in software engineering that go against the main-stream conventional
ideas. First, what if errors were a good thing that help improve the software system as 
they happen? Second, what if databases did not store data, but only gave a view of the world?

</div></div>
</div>
</section>

<div class="container outlines">
<div class="row"><div class="col-md-6" markdown="1">

### Principles of antifragile software
> **Author**: Martin Monperrus<br />
> **Critique**: Luke Church

#### Paper abstract

Have we already completely explored the software engineering noosphere with respect
to errors and reliability? I discuss an novel concept, called "software antifragility", 
that has the capacity to improve the way we engineer errors and dependability in a disruptive 
manner. This paper reviews antifragilty from classical fault tolerance to the most recent advances. 
I then explores the relation between the antifragility of the development process and the 
antifragility of the resulting software product.	

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

</div>
<div class="col-md-6" markdown="1">


### A certain tendency of the database community

> **Author**: Christopher Meiklejohn<br />
> **Critique**: Stephen Kell

#### Paper abstract

We posit that striving for distributed systems that provide "single system image" semantics 
is fundamentally flawed and at odds with how systems operate in the physical world. We realize the
database as an optimization of this system: an essential optimization that 
facilitates central data placement and ease of access to participants in a system. We motivate 
a new model of computation that is designed to address the problems of computation over 
"eventually consistent" information in a large-scale distributed system.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

</div></div>
</div>


<section>
<div class="container">
<div class="row"><div class="col-md-9" markdown="1">

## Philosophy of programming

What is programming, how does it help us understand the world and what are the origins of software
systems? The two papers in this section explore programming from a more philosophical perspective.
The first paper looks at different ways in which programming, as a scientific tool, can help us 
understand the world and the second explores stories that we tell ourselves about software.

</div></div>
</div>
</section>

<div class="container outlines">
<div class="row"><div class="col-md-6" markdown="1">

### The act of computer programming in science

> **Author**: Javier Burroni<br />
> **Critique**: Antranig Basman

#### Paper abstract

Classically, computers have been used as _knowledge discovery_ tools
insofar as the result of executing a program provides useful insight.
A secondary class of _knowledge discovery_ stems from the act of using 
a programming language. By modeling a domain, the developer can discover 
new and interesting properties of that domain. We show that programming 
languages can help their users achieve _knowledge discovery moments_ and 
outline a research program that aims to  make scientific programming more 
efficient in its ultimate goal of _knowledge discovery_.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

</div>
<div class="col-md-6" markdown="1">

### From software creationism to software evolutionism

> **Author**: François-René Rideau<br />
> **Critique**: Luke Church

#### Paper abstract

The lives we live are woven around the stories we tell. This is true
of programmers as of all humans. Now the greatest of all stories
are origin stories. In a first part, I will examine the origin stories
of software, from simple tales of software creation to elaborate
theories of software evolution. As I do, I will relate these stories to
the tools they explain and the technological realities we bring about
by following them. In a second part, I will conclude by reflecting
on storytelling and on what lies beyond. Stories are fun! And they 
subtly inform us. Let me tell you a good story...

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

</div></div>
</div>

<section>
<div class="container">
<div class="row"><div class="col-md-9" markdown="1">

## Metaphors for new paradigms

The traditional view of software components sees them as objects that hide their inner functioning
and expose a limited public interface. The papers in this section rethink this approach by looking
at other metaphors for building systems. What would we gain by seeing software more as _interlinked
documents_ or as _avatars_ that provide a working simulacrum of a part of a system.

</div></div>
</div>
</section>

<div class="container outlines">
<div class="row"><div class="col-md-6" markdown="1">

### What can software learn from hypermedia?

> **Authors**: Philip Tchernavskij, Clemens Nylandsted Klokmose, Michel Beaudouin-Lafon<br />
> **Critique**: Antranig Basman

#### Paper abstract

Most of our interactions with the digital world are mediated by
apps, but apps impose artificial limitations on the users. These 
limitations are partially due to the engineering principles 
of encapsulation and program-data separation. By contrast,
the field of hypermedia envisions flexible practices as fundamental 
features of software. We present an alternative model for software that
unifies hypermedia and interactive systems. We discuss software 
architecture that has emerged in our experimentation with Webstrates,
an experimental implementation of our model, 
and show that it subverts the principles of encapsulation and 
program-data separation.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

</div>
<div class="col-md-6" markdown="1">


### Tracing a paradigm for externalization: Avatars and the GPII Nexus

> **Authors**: Colin Clark, Antranig Basman<br />
> **Critique**: Philip Tchernavskij

#### Paper abstract

Whilst much theory and practice argues in favour of information hiding,
we find that many successful systems take a diametrically opposed approach. We name this family of systems as
those based on externalised state transfer. Rather than hiding
implementation details, these systems actively advertise their internal structure and its coordinates
via data and metadata. We discuss examples such as RESTful web applications and
MIDI devices and we discuss how we can purposefully design
new systems embodying such virtues in a more distilled form using the concept
of an _avatar_.

<p class="links"><i class="fa fa-arrow-circle-right"></i> Read the paper (coming soon)</p>

</div></div>
</div>
</article>