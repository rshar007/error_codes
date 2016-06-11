# Chapter 1: Information and Coding Theory

## Introduction
Information theory has its roots in Claude Shannon's classic paper,
`A Mathematical Theory of Communication.' In that paper, we learn of
the relationship between information, its source, and the medium we
use to transmit that information. There are three main concepts his
theory:
(i) a quantity for the measurement of information,
(ii) the relationship between information and its source, and
(iii) the relationship between information and the unreliable
channel that it is transmitted over.

Claude Shannon provides us with a theorem for channel coding:

> *If the information rate of a given source does not exceed the*
> *capacity of a given channel, then there exists a coding*
> *technique that makes possible transmission through this*
> *unreliable channel with an arbitrarily low error rate*

## Measuring Information
In information theory, we measure information using probability. If
a symbol is unlikely to follow the symbols that came before it, we
say that the symbol contains more information. Inversely, if we can
reliably predict the symbol's occurence, we say that the symbol contains
little information.

Shannon gives us a formula that defines a measure of information:

$I_i \equiv -\log_{b}P_i = \log_{b}\left( \frac{1}{P_i}\right)$
