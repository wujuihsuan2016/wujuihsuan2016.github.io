---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: profile.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Bureau M7 310</p>
    <p>46 Allée d'Italie</p>
    <p>69364 Lyon Cedex 07</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 6 # leave blank to include all the news in the `_news` folder

#latest_posts:
#  enabled: false
#  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#  limit: 3 # leave blank to include all the blog posts
---

Hi! I am Jui-Hsuan Wu! I am a postdoctoral researcher in the [Plume](https://www.ens-lyon.fr/LIP/PLUME/) team, [LIP](https://www.ens-lyon.fr/LIP/), ENS Lyon, funded by the ANR project [RECIPROG](https://www.irif.fr/reciprog/index). I also go by the name Ray.

Previously, I was a PhD student at [LIX](https://www.lix.polytechnique.fr/), 
[Ecole Polytechnique](https://www.polytechnique.edu/en) & [Inria](https://www.inria.fr/en) Saclay advised by [Dale Miller](http://www.lix.polytechnique.fr/Labo/Dale.Miller/) and [Beniamino Accattoli](https://sites.google.com/site/beniaminoaccattoli/). Even before, I studied computer science and mathematics at [Ecole Normale Supérieure](https://www.ens.psl.eu/) and got a master degree from [Master Parisien de Recherche en Informatique](https://wikimpri.dptinfo.ens-cachan.fr/doku.php).
You can have a look at my [CV](assets/pdf/CV.pdf) ([Version française](assets/pdf/CVfr.pdf)).

### Research interests
- Proof theory
- Logic
- $$\lambda$$-calculus
- Functional programming

### Current research

The goal of my PhD project is to design/study term structures based on some well-chosen proof system, in the hope
that proof-theoretic considerations will on one hand provide careful and formal descriptions of term structures and on the other hand give us more insights on terms.

Instead of using proof systems such as Gentzen's natural deduction and sequent
calculus, we use the [focused](https://en.wikipedia.org/wiki/Focused_proof)
proof system LJF in order to give more structure to proofs. The notion of
**polarization** gives the flexibility to construct differents forms of proofs,
which is a desirable feature since we want to be able to describe different term structures
in our system. In particular, we consider the negative (resp. positive)
polarization, that is, the one that assigns the negative (resp. positive)
polarity to each atom. This two polarizations induce two very different styles
of term structures. Intuitively, the negative polarization yields the usual
tree-like syntax, without any possible sharing within a term, while the positive
polarization yields a syntax where sharing is possible within a term via some
specific form of explicit substitutions (or let-expressions). Based on this
approach, we also propose a positive presentation of $$\lambda$$-terms, called
positive $$\lambda$$-terms (negative $$\lambda$$-terms coincide with usual
$$\lambda$$-terms). See our [CSL2023 paper](assets/pdf/csl2023-techrep.pdf) for more
details.

A key point in our CSL paper is that ($$\lambda$$-)terms correspond to cut-free
proofs. This means that the usual computation-as-proof-normalization approach
would not work in our setting. For this, I proposed another approach which
involves some proof transformation (that transforms a cut-free proof into a
proof with cuts) and cut-elimination. Such an approach is however not universal,
it is should be seen as a recipe that one could follow and adapt based on his/her
purposes. The untyped $$\lambda$$-calculus can be defined from negative/usual
$$\lambda$$-terms in this way. What about positive $$\lambda$$-terms?
Following a similar idea, I defined the **positive $$\lambda$$-calculus** and show its
reduction is compatible with the beta-reduction of the $$\lambda$$-calculus in a meaningful way. Since positive $$\lambda$$-terms involve a number of let-expressions,
it is natural to consider the equivalence based on permutable or parallel let's, namely the structural equivalence.
For this, I defined $$\lambda$$-graphs with bodies, essentially DAGs
with some additional structure to deal with bindings, that capture the structural equivalence on positive $$\lambda$$-terms. See my [APLAS2023 paper](assets/pdf/APLAS2023.pdf) for more details.

Recently, I worked with Beniamino Accattoli on a connection between the positive $$\lambda$$-calculus and **usefulness**, a notion of reduction with sharing first introduced to study reasonable cost models. You can find more details in our MFPS2024 paper.

### Misc

I am from New Taipei, Taiwan. 

Find out how my name is pronouced: [Jui, 睿](https://forvo.com/word/%E7%9D%BF/#zh) (sounds like ray in English) and [Hsuan, 軒](https://forvo.com/word/%E8%BB%92/#zh).

Take a look at [APLL](https://github.com/wujuihsuan2016/LL_prover), an automated prover for propositional
[linear logic](https://en.wikipedia.org/wiki/Linear_logic) designed and implemented by me.

I am an amateur [go](https://en.wikipedia.org/wiki/Go_(game)) player. I used to be a 6-dan player (a long time ago) back in Taiwan.

I am a music enthusiast. I mainly listen to Hip Hop, R&B, and Jazz. My favorite
artists are [Soft Lipa](https://www.youtube.com/watch?v=xPU-cgPjZKk), [Loyle Carner](https://www.youtube.com/watch?v=1GmuDka6pbk),
[FKJ](https://www.youtube.com/watch?v=qU5FWU0SH0o), [Mac Miller](https://www.youtube.com/watch?v=aIHF7u9Wwiw),
[H.E.R.](https://www.youtube.com/watch?v=vBy7FaapGRo),
[Nick Hakim](https://www.youtube.com/watch?v=N83D8KUeCqs), [Sunset Rollercoaster](https://www.youtube.com/watch?v=wNp7WJusiHQ), ...

I recently got into [French touch](https://en.wikipedia.org/wiki/French_house) music: [Modjo](https://www.youtube.com/watch?v=mMfxI3r_LyA), [Étienne de Crécy](https://www.youtube.com/watch?v=Hu4dTob8avQ), [Cassius](https://www.youtube.com/watch?v=lXhl9Sey6l8), [Breakbot](https://www.youtube.com/watch?v=6okxuiiHx2w), and of course the one and only [Daft Punk](https://www.youtube.com/watch?v=K0HSD_i2DvA).

My brother is a freelance image maker, check out his works [here](http://wujuiche.com/).

<center><iframe src="https://free.timeanddate.com/countdown/i9ftwgtd/n195/cf11/cm0/cu4/ct0/cs0/ca0/co1/cr0/ss0/cac000/cpc111/pceee/tc66c/fn3/fs100/szw320/szh135/tatTime%20left%20to%20Event%20in/tac000/tptI%20have%20been%20in%20France%20for/tpc111/iso2015-07-18T07:30:00" allowtransparency="true" frameborder="0" width="336" height="36"></iframe></center>