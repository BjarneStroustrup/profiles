# ``Profiles'' -- What we need

What do we need to make “profiles” an industry-wide tool for the variety of C++ safety needs?
Profiles is a framework. Many parts have to be created and fitted in to enable widespread use. Much has been done, but relatively little is widely available. This is a wish list. Please help in whichever capacity you can.
Remember, you have to give a rationale. You cannot assume that others will appreciate your suggestion or design without seeing your reasoning.


Needs
  - Set of profiles – what profiles do we need? which should be part of an initial set? Which should be standardized? Which should be defined as unions of other profiles?

  - How do we specify a profile? As a set of guarantees; not, simply as a set of detailed rules. We need examples of profiles: both the set of guarantees and an initial set of detailed rules for delivering those guarantees.

  - The Core Guidelines has been our initial proving ground for rules for good (and often safe C++ code). We need more rules and rules taking advantage of C++20 and C++23. Individual suggestions can be made directly on the CG GitHub, but larger sets of suggestions and suggestions directly related to profiles belong here.

  - Comments/analysis on how various compilers could accommodate profiles.

  - Comments/analysis on how various static analyzers could accommodate profiles.

  - Names of individuals and groups working on profiles and similar projects.


The Profiles github is https://github.com/BjarneStroustrup/profiles

## References

- B. Stroustrup and G. Dos Reis: [Safety Profiles: Type-and-resource Safe programming in ISO Standard C++](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2023/p2816r0.pdf). P2816

- B. Stroustrup and G. Dos Reis: [Design Alternatives for Type-and-Resource Safe C++](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2022/p2687r0.pdf). P2687R0. 2022-20-15

- B. Stroustrup: [Type-and-resource safety in modern C++](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2021/p2410r0.pdf). P2410r0. 2021-07-12.

- B. Stroustrup, H. Sutter, and G. Dos Reis: [A brief introduction to C++'s model for type- and resource-safety](https://www.stroustrup.com/resource-model.pdf). October 2015. Revised December 2015.

- B. Stroustrup: [Writing Good C++14](https://www.youtube.com/watch?v=1OEu9C51K2A).  CppCon 2015.

- [The C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md).

- [The Core Guidelines Support Library (GSL)](https://github.com/microsoft/gsl).

- H. Sutter: [Lifetime safety: Preventing common dangling](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1179r1.pdf). P1179R1. 2019-11-22.


