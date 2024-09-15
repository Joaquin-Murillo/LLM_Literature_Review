# LLM Literature Review
By Joaquin Murillo

## Questions for ChatGPT:
There have been countless programming languages created throughout history. But why do some languages become extinct, while others become built upon and iterated? What reasons lead to some programming languages becoming forgotten while others stayed relevant? Were there any external reasons that led to these outcomes? What are some examples of programming languages that have been adapted over time?

## References:
* ["Programming Languages: Principles and Paradigms" by Maurizio Gabbrielli and Simone Martini](https://link.springer.com/book/10.1007/978-1-84882-914-5)
* ["The Design and Evolution of C++" by Bjarne Stroustrup](https://www.stroustrup.com/dne.html)
* ["Concepts of Programming Languages" by Robert W. Sebesta](https://www.sci.brooklyn.cuny.edu/~chuang/books/sebesta.pdf)
* ["Structure and Interpretation of Computer Programs" by Harold Abelson and Gerald Jay Sussman](https://sarabander.github.io/sicp/html/index.xhtml)

# Chatting with ChatGPT
### Brief History of Programming Languages
#### Assembly ➔ High-Level Languages ➔ Domain-Specific Languages (DSLs)
* Evolution: Early programming was done in assembly language, which is hardware-specific and low-level. The development of high-level languages like Fortran, COBOL, and later languages like Python and Java abstracted away hardware details.
* Adaptation: Domain-Specific Languages (DSLs) like SQL for databases or HTML/CSS for web development evolved to address specific problem domains, improving developer productivity by providing specialized syntax and features.

### Factors Leading to the Extinction or Survival of Programming Languages
1. Technological Evolution
* Advancements in Hardware and Software: As computing hardware evolves, languages that cannot leverage new capabilities or address new challenges (like parallel processing or cloud computing) may become obsolete.
* Language Features and Capabilities: Languages that lack modern features (such as object-oriented programming, functional programming paradigms, or strong typing) may be left behind in favor of more robust options.

2. Corporate and Institutional Backing
* Industry Adoption: Languages adopted by major corporations or industries often have longer lifespans due to the investment in existing codebases.
* Educational Institutions: Languages taught in universities and schools become ingrained in the skills of new developers, promoting their use in professional settings.

3. Economic Factors
* Cost of Training and Development: If a language requires significant investment to train developers, companies might prefer more commonly known languages.
* Market Demand: Languages not in demand may be dropped from curriculums and job requirements, leading to a decline in skilled developers.

### Features of Certain Languages That Keep Them Relevant
1. Lack of Standardization and Maintenance
* Obsolescence: Without ongoing maintenance and updates, languages can become incompatible with new systems or fail to meet current security standards.
* Standardization: Languages that lack formal standards may fragment, leading to incompatibilities and reduced adoption.

2. Competition from Superior Languages
* Better Alternatives: Newer languages may offer improved performance, easier syntax, or better tools, leading developers to migrate.
* Niche Applications: Languages designed for specific tasks may become obsolete if those tasks are better handled by more versatile languages.

3.  Poor Performance and Scalability
* Inefficiency: Languages that cannot handle large-scale applications efficiently are often abandoned in favor of more performant options.
* Inability to Scale: In the era of big data and high-traffic applications, scalability is crucial.

4. Community and Ecosystem Support
* Developer Community: A strong, active community contributes to the longevity of a language by providing libraries, tools, and support.
* Ecosystem and Libraries: Languages with rich ecosystems and extensive libraries make development faster and more efficient, encouraging continued use.

5. Open Source vs. Proprietary
* Accessibility: Open-source languages allow for community contributions and adaptations, fostering growth and relevance.
* Proprietary Restrictions: Languages that are proprietary may suffer from limited adoption due to licensing costs or restrictions.

### External Reasons Affecting the Outcomes
1. Changes in Industry Trends
* Emerging Technologies: The rise of mobile computing, web development, artificial intelligence, and cloud services shifts the demand toward languages suited for these fields.
* Regulatory Changes: Legal requirements for security and data protection can make certain languages less favorable.

2. Cultural and Educational Influences
* Education Curricula: The programming languages taught in schools influence which languages new developers learn and use.
* Open Source Movement: The rise of open-source software has boosted languages that support collaborative development.

### Examples of Programming Languages Adapted Over Time
1. C ➔ C++ ➔ C#
* Evolution:
  * C: Developed in the early 1970s for system programming.
  * C++: Introduced in the 1980s, adding object-oriented features, templates, and exception handling to C.
  * C#: Released by Microsoft in 2000 as part of its .NET initiative, combining principles from C and C++ with a focus on simplicity and modern programming paradigms.
* Adaptation: Each language builds upon its predecessor to address new programming needs while maintaining some syntactic familiarity.

2. JavaScript ➔ Node.js / Express.js / React / Vue.js / Angular
* Evolution: Originally a client-side scripting language, JavaScript has expanded to server-side development and complex front-end applications.
* Node.js: A runtime environment that allows JavaScript to run on the server side.
* Express.js: A minimal and flexible Node.js web application framework that provides robust features for web and mobile applications.
React, Vue.js, Angular: Front-end JavaScript frameworks and libraries that facilitate building complex user interfaces.
* Adaptation: Javascript has maintained continued relevance due its various highly popular frameworks, allowing it to become a key leader in web development.

4. Python ➔ Python 2 ➔ Python 3
* Evolution:
  * Python: It was released in 1991 by Guido van Rossum.
  * Python 2: Released in 2000, it became widely popular due to its simplicity and readability.
  * Python 3: Introduced in 2008, Python 3 made significant changes to improve consistency and eliminate redundancies, such as better Unicode support and revamped syntax.
* Adaptation: Despite initial resistance due to backward incompatibility, the community has largely transitioned to Python 3, ensuring the language's continued relevance.

3. PHP 4 ➔ PHP 5 ➔ PHP 7 ➔ PHP 8
* Evolution:
  * PHP 4 & 5: Early versions focused on web scripting with basic object-oriented features.
  * PHP 7: Introduced in 2015 with significant performance improvements and scalar type declarations.
  * PHP 8: Released in 2020, adding a Just-In-Time (JIT) compiler and union types.
* Adaptation: Continuous enhancements keep PHP relevant for modern web development.

## Influential Researchers in the Field:
1. Leo A. Meyerovich
* Leo A. Meyerovich is known for his empirical studies on programming language adoption and the social factors influencing it.
* Key Papers:
  * [Empirical Analysis of Programming Language Adoption](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=3pnyo7IAAAAJ&citation_for_view=3pnyo7IAAAAJ:kNdYIx-mwKoC). Meyerovich, L. A., & Rabkin, A. S. (2013).
  * [Socio-PLT: Principles for Programming Language Adoption](https://dl.acm.org/doi/abs/10.1145/2384592.2384597?casa_token=WE8S5lBXvkYAAAAA:QnBo3sHESuGtj-lFwmi0m876Otnr8jrDVfUmygPfbiKg33A_Vr8pHl0w6dmKhkMM6qCUPqy3qnpW6A). Meyerovich, L. A., & Rabkin, A. S. (2012).

2. Andreas Stefik
* Andreas Stefik is known for his study of human factors in programming languages, accessibility, and programming language design for education.
* Key Papers:
  * [An Empirical Investigation into Programming Language Syntax](https://dl.acm.org/doi/abs/10.1145/2534973?casa_token=CTKEoTDwFF0AAAAA:mQE7NoqzYrWSOohguc2EuOFruONH53he08CrvPC92zB6DGGz9Y6vJzHw7RI0hHlt4TfabYaxUCaxJA). Stefik, A., & Siebert, S. (2013). ACM Transactions on Computing Education (TOCE). 

3. Simon Peyton Jones
* Simon Peyton Jones is widely recognized for his studies on functional programming languages, type systems, compiler design (notably Haskell).
* Key Papers:
  * [The Implementation of Functional Programming Languages](https://dl.acm.org/doi/abs/10.5555/1096899). Peyton Jones, S. L. (1987). Prentice Hall International Series in Computer Science.

## Summary
Programming languages have had a long and storied history, evolving from low-level assembly language to the highly optimized high-level languages we know today. However, not every language withstood the test of time. This was due to a multitude of reasons, from a lack of community support, poor technical performance, low adaptability, and handful of external factors.
