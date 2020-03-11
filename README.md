# demo1920corsoa
Repository dell'a.a. 2019-2020 del corso A

Silvio Micali 
Italia

Silvio Micali is a visionary whose work has contributed to the mathematical foundations of cryptography and has advanced the theory of computation. His non-conventional thinking has fundamentally changed our understanding of basic notions such as randomness, secrets, proof, knowledge, collusion, and privacy, which have been contemplated and debated for millennia. This foundational work was a key component in the development of the computer security industry, facilitated by his patents and start-up companies. His work has also had great impact on other research areas in computer science and mathematics.

Silvio’s educational and teaching talents are no less legendary. His lectures are consistently entertaining and illuminating. They use numerous cartoons and remarkable stories of unlikely heroes, villains and impossible tasks, designed to highlight the new ideas and concepts. His strong Sicilian accent is the perfect spice for these treats. Silvio has mentored and advised many PhD students in that spirit.

Cryptography

Micali’s work with Goldwasser (his co-winner of the Turing award and long-time collaborator) helped make cryptography a precise science. The mathematical structures they created, including formal notions of privacy, adversaries, pseudorandomness, interactive proofs, zero-knowledge proof, and numerous other basic notions that are often extremely subtle to formulate, set cryptography on rigorous foundations of the highest standards, and opened up whole new areas of research within computer science.

Their revolutionary first paper, written when they were graduate students, is “Probabilistic Encryption,” [1], one of the most influential papers in the history of computer science. It set the foundations on which thousands of researchers base their work.

The first question asked and answered in this paper is “What is a secret?” This very basic question had never been formally addressed, despite centuries of research in cryptography and an ancient natural human interest in the notion. They set very high standards: an adversary should not be able to gain even partial information about a secret. In this paper they define probabilistic encryption, semantic security, and also computational indistinguishability, the notion that objects which look the same to efficient algorithms are the same. Using these concepts they are able to make formal sense of Diffie & Hellman’s [10] ideas of computational cryptography. They combine all these to give a public-key encryption scheme which is secure by their standard: they prove that any leak will result in an efficient algorithm for factoring integers. Such formal definitions and proofs are missing from previous seminal papers like Diffie & Hellman and RSA [11] of R. L. Rivest, A. Shamir and L. Adleman. Micali and Goldwasser’s first paper paved the way for them and numerous others to advance the rich and important field of cryptography, which was critical to the development of commercial applications of the Internet.

Randomness

The issues and techniques raised by cryptographic research have led to exciting developments in other areas in the theory of computation, such as the study of “computational randomness”, or “pseudorandomness”. This field has matured in the past 20 years and produced such fundamental results as the ability to convert hard functions into pseudorandom objects, and the ability to extract randomness from defective random sources. Micali’s paper with his advisor Manuel Blum, [2] constructs a “pseudo-random generator”, which deterministically and efficiently stretches a short random seed into a long sequence of bits, and then proves this sequence is completely unpredictable by any efficient algorithm, assuming the hardness of the discrete logarithm function. This idea is elaborated in his PhD thesis, the title of which, Hardness vs. Randomness, has come to denote a central paradigm used today to allow the removal of randomness from probabilistic algorithms. Another magical construct of Micali (in a paper with Goldreich and Goldwasser [3]) is a “pseudo-random function” whose output is indistinguishable from that of a truly random one. These have proven fundamental not only in cryptography, but in other fields. For example (as shown by Les Valient and Mike Kearns), they yield limitations in computational learning theory, and partly explain our inability to prove computational lower bounds (such as P ¹ NP).

Interactive Proofs

Yet another field which emerged from cryptographic concerns (mainly from Micali’s joint paper with Goldwasser and Rackoff [4]) is the field of “interactive proofs.” Such proofs generalize the ancient notion of mathematical proof by allowing interaction, randomization and error, thus vastly enriching meaning and utility. In 20 years this concept has given rise to fundamental discoveries in computational complexity, such as IP=PSPACE and the PCP Theorem, and has had a fundamental impact on understanding the hardness of approximation. The same paper defines the paradoxical notion of “zero-knowledge” proofs that are convincing but reveal nothing beyond their validity. In two follow-up papers (with Goldreich and Wigderson [5], [6]) Micali showed that this notion is universal; assuming one-way functions, every theorem has such a “zero-knowledge” proof. This resolves problems such as those involving basic copyright issues. It also enables a remarkably general design tool for cryptographers: a compiler which transforms any cryptographic protocol designed for honest, cooperating parties into one which can tolerate arbitrary malicious behavior.

Silvio and Shafi’s originality and foresight are inspirational, and their work holds computational proofs to the most stringent mathematical standards. They have trained a generation of students and colleagues to be equally bold and creative.

Mechanism Design.

In the past few years Micali turned his attention to Game Theory. In particular, he has been working on developing a more robust form of mechanism design, in which collusion and privacy are explicitly taken into account. Collusion and privacy have always played a central role in our human endeavors, but until this work they had not been central to game theoretic analysis.

Practical impact

Complementing his academic work, Micali has many patents on practical implementations of his inventions for encryption, digital signatures, electronic cash, certified transactions, key-escrow and more. It is highly unusual for a theoretician to be awarded over 50 patents. His practical bent goes further, with the creation of two start-up companies: Peppercoin (for micro-payments), which was acquired by Chockstone in 2007, and CoreStreet (for real-time credentials) which was acquired by ActiveIDentity in 2009.

Cooking

Well, if you never had Silvio cook one of his mother’s recipes for you, it is very hard to explain what you are missing.

Summary

Micali is an intellectual giant of a rare variety. His leadership has steered the academic agenda of our field in the key areas. Time and time again his ideas challenged conventional wisdom with originality, vision and technique, to create what would become tomorrow's better conventional wisdom.

Author: Avi Wigderson