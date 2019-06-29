# Operator-Listcat

A module that adds operators and methods for merging lists
in a clean way. See:

## [Perl 6 Needs a List Concatenation Op](http://ajs.github.io/tools/perl-6-list-concat-op/)

From that article:

There are three things here:

* The infix operator `listcat` that works as `<a b c> listcat <x y z>` and
  returns `<a b c x y z>` but without flattening and further than one level.
* The Unicode alias `⊕` for listcat that evokes the Python (among a small
  number of other languages') convention of using
  `+` for this purpose without actually muddying the type waters.
* A modification to `List` that adds the `sling` method that performs
  a `listcat` between the `List` object that it's called on and its
  arguments, returning the unified list.
