# Master&rsquo;s seminars

This repository contains the scripts of the two talks I gave in two seminars of my M.Sc. Mathematics at the [TUM](https://www.tum.de/).

## Seminar in Toric Varieties

This seminar took place in the Summer semester 2022 under the supervision of Professor Christian Liedtke.

In toric geometry, one associates to a convex polytope, whose vertices are the points of some lattice, an algebraic variety called an **affine toric variety**. Then, different affine toric varieties can be glued together to give rise to the **(general) toric varieties**. This construction represents an example of explicit algebraic geometry and it serves as a test ground for conjectures.

### Talk 3: Affine Toric Varieties

I gave talk 3 of this seminar, for which I used this [script](Toric-Varieties/Talk-3-Affine-Toric-Varieties.pdf). It was about the construction of affine toric varieties.

First of all, given a monoid *S*, one can construct the &Copf;-algebra &Copf;[*S*] as a free &Copf;-vector space of base *S*, with the multiplication defined by the operation of the monoid. This way, the generators of *S* as a monoid are the generators of &Copf;[*S*] as a &Copf;-algebra.

Then, Hilbert&rsquo;s Nullstellensatz gives a bijection between the algebraic variety defined by a polynomial in &Copf; and the maximal spectrum of its assocated affine &Copf;-algebra. Hence, the spectrum of an affine &Copf;-algebra can be seen geometrically as an algebraic variety.

Finally, a strongly convex rational polytope *&sigma;* &ndash; in a lattice of &Ropf;<sup>*n*</sup> &ndash; is a finitely generated monoid, and so is its dual *S*<sub>*&sigma;*</sub>. Hence we can construct its associated &Copf;-algebra &Copf;[*S*<sub>*&sigma;*</sub>], whose spectrum is an affine variety over &Copf; called **affine toric variety**. Their name is due to the fact that they contain a torus (&Copf;&ast;)<sup>*n*</sup> that gives them a group structure.

### References

[1] R. Hartshorne, *Algebraic Geometry*, vol. 52 Springer Science &amp; Business Media, 2013.

[2] W. Fulton, *Introduction to toric varieties*, Annals of Mathematics Studies 131, Princeton University Press, 1993.

## Seminar in Classification of Algebraic Varieties

This seminar took place in the Winter semester 2023/2024 under the supervision of Professor Christian Liedtke.

The ultimate goal of algebraic geometry is the classification of algebraic varieties. Although this goal is currently completely out of reach, great progress has been made in the classification of low-dimensional algebraic varieties.

### Talk 2: Curves of Small Genus

I gave talk 2 of this seminar, for which I used this [script](Classification-of-Algebraic-Varieties/Talk-2-Curves-of-small-genus.pdf). It was about the explicit classification of **non-hyperelliptic curves** of genus 3, 4, and 5.

Non-hyperelliptic curves can be embedded into the projective space through their **canonical embedding**. This reduces the classification of non-hyperelliptic curves to the study of the homogeneous polynomials that realise them as curves in the projective space. The coefficients of these polynomials parametrise the curves. This parametrisation gives the set of isomorphism classes of curves of certain genus a structure of an algebraic variety, which makes this set a **variety of moduli**.

This procedure works fine for small genus, but gets harder as genus increases. Eventually, moduli spaces of curves of sufficiently large genus don&rsquo;t admit a scheme structure.

### References

[1] R. Hartshorne, *Algebraic Geometry*, vol. 52 Springer Science &amp; Business Media, 2013.

[2] A. Egbert, *Solutions to Hartshorne&rsquo;s Algebraic Geometry*, [https://github.com/myzhang24/hartshorne-solution](https://github.com/myzhang24/hartshorne-solution), 2013.
