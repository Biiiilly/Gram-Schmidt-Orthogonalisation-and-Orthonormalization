# Gram-Schmidt Orthogonalisation and Orthonormalization

# Installation

You can download the package with the following command line:

`leanproject get Biiiilly/Gram-Schmidt-Orthogonalisation-and-Orthonormalization`

It's also been merged into `marthlib`, you can look it up in `src/analysis/inner_product_space/gram_schmidt_ortho`

# Introduction

In this file we introduce Gram-Schmidt Orthogonalization and Orthonormalization.

The Gram-Schmidt process takes a set of vectors as input
and outputs a set of orthogonal vectors which have the same span.

# Main results

- `gram_schmidt` : the Gram-Schmidt process
- `gram_schmidt_orthogonal` :
  `gram_schmidt` produces an orthogonal system of vectors.
- `span_gram_schmidt` :
  `gram_schmidt` preserves span of vectors.
- `gram_schmidt_ne_zero` :
  If the input of the first `n + 1` vectors of `gram_schmidt` are linearly independent,
  then the output of the first `n + 1` vectors are non-zero.
- `gram_schmidt_normed` :
  the normalized `gram_schmidt` (i.e each vector in `gram_schmidt_normed` has unit length.)
- `gram_schmidt_orthornormal` :
  `gram_schmidt_normed` produces an orthornormal system of vectors.
