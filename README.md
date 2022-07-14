# Convolution arithmetic

A technical report on convolution arithmetic in the context of deep learning.

The code and the images of this tutorial are free to use as regulated by the 
licence and subject to proper attribution:

* \[1\] Vincent Dumoulin, Francesco Visin - [A guide to convolution arithmetic
  for deep learning](https://arxiv.org/abs/1603.07285)
  ([BibTeX](https://gist.github.com/fvisin/165ca9935392fa9600a6c94664a01214))

## Setting up conda environment

From the repository's root directory:

``` bash
$ conda env create -f environment.yaml
```

## Setting up output folders

From the repository's root directory:

``` bash
$ mkdir gif && mkdir png && mkdir pdf
```

## Generating the pdfs for the thesis

From the repository's root directory:

``` bash
$ conda activate conv_arithmetic
$ make thesis
```

The resulting pdfs will be output to the `pdf`.

