# LLM-Literature-Review

## Questions

How have object-oriented, imperative, and functional programming languages differed in their development? Additionally, how would the nature of each category of programming language affect its respective degree of adoption for pedagogical purposes?


## ChatGPT-Generated Response

With regard to the specific differences in development and adoption, ChatGPT wrote the folllowing (emphasis has been added for the sake of clarity):

### Paradigm Complexity and Learning Curve:

***Imperative languages*** are often easier to learn and teach since they closely map to how computers execute tasks, which has helped them gain widespread adoption among beginners.
***Object-oriented*** languages balance abstraction with understandability. They tend to be more complex than imperative languages but are widely used due to their alignment with software design principles (encapsulation, inheritance, polymorphism).
***Functional languages*** offer a high level of abstraction and mathematical elegance, which can lead to more concise and maintainable code, but they require a deeper understanding of advanced concepts like recursion and immutability, slowing initial adoption.

### Use Cases and Industry Needs:

***Imperative languages*** are well-suited to system-level programming and applications where direct control over the hardware is required (e.g., embedded systems, operating systems).
***Object-oriented languages*** have thrived in enterprise applications, GUIs, and larger codebases where modularity, reuse, and maintainability are priorities.
***Functional languages*** have seen increased adoption in fields that require parallelism, fault tolerance, and scalability (e.g., data science, financial systems, distributed computing). However, functional programming remains less common in many industries, although the adoption of functional techniques in hybrid languages is growing.

### Hybridization and Evolution:

Many modern languages combine paradigms. For example, Python, JavaScript, and Scala incorporate functional programming features while maintaining support for imperative and object-oriented styles.
This hybrid nature has accelerated the adoption of paradigms like functional programming without requiring developers to entirely switch from imperative or Object-oriented practices.

### Conclusion:

In summary, ***imperative languages*** are ideal for introductory programming due to their simplicity, ***object-oriented languages*** are great for teaching students how to manage complex systems, and ***functional languages*** are valuable for developing mathematically robust thinking, clean code practices, and managing concurrency. Each paradigm emphasizes different problem-solving strategies, which can shape the development of a student's programming mindset.

## Summary 

Imperative programming languages were the first to be developed. Their inherently basic nature (that is, issuing statements for a computer to execute in the form of programs) made it the most logical step from machine language. This would ultimately set the groundwork for future paradigms. Their simplistic nature makes them ideal for being taught to beginners in coding, which is why Python and C++ are often used in introductory college-level programming courses. For younger students (i.e., those in middle school), there exist a plethora of other imperative block-based languages that can serve as a springboard to coding. The web-based language Scratch, for instance, is often used to introduce students to basic computer logic.

The advent of object-oriented programming introduced several new notions, such as encapsulation and polymorphism. The modular nature of object-oriented principles broke down problems and structured them into separate components, allowing developers to complete more complex tasks. Intermediate-level programmers can relate the idea of division of software into objects to real-world concepts, making object-oriented languages the logical next step from imperative languages. Java is perhaps the most renowned language belonging to this hierarchy given that it is almost purely object-oriented (as opposed to other languages, which can be a hybridization of multiple paradigms). Not all object-oriented languages share the same traits. For example, some contain classes, but others do not; this leads to distinct programming patterns even within the paradigm.

Functional languages essentially evolved alongside both imperative and object-oriented languages due to them being composed of functions. Haskell and Lisp are modern examples of such languages and are often only taught in an advanced academic setting---the self-taught learner may not touch upon one. The logic-based nature of the paradigm makes it ideal for experimenting with parallelism and concurrency.

As mentioned above, certain languages implement elements from multiple different paradigms. C#, for example, is both object-oriented and functional in nature. This makes it optimal for creating a course that simultaneously builds upon what students may already know and teaches more complex concepts regarding parallelism. The selection of a programming language (or multiple) to teach during a course essentially defines its academic level.


## References

- Krishnamurthi, S., & Fisler, K. (2019). [13 Programming Paradigms and Beyond](https://books.google.com/books?id=vmAwEAAAQBAJ&lpg=PA377&ots=1msDHU7ZcC&dq=programming%20paradigms&lr&pg=PA377#v=onepage&q=programming%20paradigms&f=false). The Cambridge Handbook of Computing Education Research.
- Sajaniemi, J., Ben-Ari, M., Byckling, P., Gerdt, P., & Kulikova, Y. (2006). [Roles of variables in three programming paradigms](https://doi.org/10.1080/08993400600874584). Computer Science Education, 16(4), 261–279.
- Gorodniaia, L., & Andreyeva, T. (2016). [Study of programming paradigms](https://doi.org/10.21125/inted.2016.0768). INTED2016 Proceedings, 1, 7482–7491.
- Dobre, C., & Xhafa, F. (2013). [Parallel programming paradigms and frameworks in Big Data Era](https://doi.org/10.1007/s10766-013-0272-7). International Journal of Parallel Programming, 42(5), 710–738.
- Maloney, J., Resnick, M., Rusk, N., Silverman, B., & Eastmond, E. (2010). [The Scratch Programming Language and Environment](https://doi.org/10.1145/1868358.1868363). ACM Transactions on Computing Education, 10(4), 1–15.
- Ortin, F., Redondo, J. M., & Quiroga, J. (2017). [Design and evaluation of an alternative programming paradigms course](https://doi.org/10.1016/j.tele.2016.09.014). Telematics and Informatics, 34(6), 813–823.

