# jthread

C++ class for a joining and cooperative interruptible thread (std::jthread) with stop_token helper-
- Reference implementation
- Test suite
- Papers proposing it for the C++ standard
  -  http://wg21.link/p0660  (main proposal for C++20)
     - http://wg21.link/p1287  (initial proposal for stop callbacks, merged with p0660r7)
  -  http://wg21.link/p1869  (additional minor updates for C++20)

Main authors:  Nicolai Josuttis (http://www.josuttis.com/contact.html) and Lewis Baker

[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
 
The code is licensed under a Creative Commons [Attribution 4.0 International License][cc-by]. 

TOC:
====

<b>source/</b>
- source code for the reference implementation
  and the test suite
  - to test the CV class extensions they are applied to a class condition_variable_any2

<b>tex/</b>
- final paper and proposed wording using C++ standard LaTeX style
  - to create the latest version:  <b>pdflatex std</b> 

<b>doc/</b>
- current and old documentations
  - all proposals P0660*.pdf

