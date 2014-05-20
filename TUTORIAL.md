##Step 0—Introduction##

See the README for setup instructions.

This tiny Haskell program makes use of quite a few language features, from the top down:

* [Module declaration][module]
* [Libraries from Hackage and the Haskell Platform][imports]
* [Function definition, the function application operator `$`, and the `IO` monad][main]
* [Point-free composition of higher-order functions, partial application, and functors][renderTree]
* [Tuples][buildTree]
* [Point-wise function definition, pattern matching and arrays][drawBranch]
* [Guards][guards]
* [The `where` clause and the use of the _prime_ or apostrophe in names][where]
* [Custom operators, in this case `.+^` from the diagrams library][operators]
* [Nested functions and a post-application form of pipeline][nested]
* Type inference—no link to code because it's the _lack_ of type declarations
* Lazy evaluation, class instances, and currying—implicit in most Haskell code

I would have liked to add _inifinite data structures_ to the list, but I'm not
using any.

Look at the unadorned [code][code].

[code]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs
[module]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L1
[imports]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L2-L4
[main]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L6
[renderTree]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L7
[buildTree]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L8
[drawBranch]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L9
[guards]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L11-L12
[where]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L13
[operators]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L14
[nested]: https://github.com/bobgru/nonsense/blob/branch-0/DrawTree.hs#L15
