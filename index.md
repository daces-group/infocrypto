# ECE598DA Topics in Information-Theoretic Cryptography

## Description
In this course, we will study foundational and recent work on the use of information theory to design and analyze cryptographic protocols. We will begin by studying privacy attacks which motivate strong privacy and security definitions. Then, we will explore the basics of differential privacy and study some core works on zero-knowledge proofs. Finally, we will explore various applications, including watermarking of generative models and basic quantum cryptography protocols.

## Meeting Times/Days
1hr 20 mins (9:30AM - 10:50AM) on Tuesdays and Thursdays

## Location
Room 2015 in the Electrical & Computer Engineering Building

## Instructor
[Daniel Alabi](http://alabidan.me)

Office Hours: 11AM-12PM on Tuesdays (CSL 118) and by appointment

## Prerequisites

*	At least one of:
    - ECE 313/MATH 362: Probability with Engineering Applications
    - MATH 461: Probability Theory
*	ECE/CS 374: Introduction to Algorithms and Models of Computation

Prerequisite overrides will be considered by the instructor on a case-by-case basis.

## Recommended Textbooks

- *Introduction to Cryptography with Coding Theory*. By Wade Trappe, Lawrence C. Washington.

- *Tutorials on the Foundations of Cryptography*. Edited by Yehuda Lindell.

## Schedule

**Week 1**: Introduction: motivations, one-time pad review, [talking drums](https://www.youtube.com/watch?v=B4oQJZ2TEVI), probability theory review

Readings:
* Chapter 1 of *The Information* by James Gleick
* Chapters 1-3 of *Introduction to Probability Models* by Sheldon Ross

[Exercises for Week 1](exercises/week1.pdf)

**Week 2**: Attacks on Privacy, Security, Valuation

Readings:
* Chapter 1, Chapter 2, Chapter 4 of Trappe-Washington
* Dinur-Nissim [attack](https://dl.acm.org/doi/10.1145/773153.773173)

[Exercises for Week 2](exercises/week2.pdf)

**Week 3**: Standard Mechanisms for Differential Privacy and Composition

Readings:
*  Chapters 1 and 2 of [Vadhan](https://salil.seas.harvard.edu/sites/g/files/omnuum4266/files/salil/files/the_complexity_of_differential_privacy.pdf)

[Exercises for Week 3](exercises/week3.pdf)

**Week 4**: Information-Theoretic Lower Bounds for Differential Privacy

Readings:
* Chapter 5 of [Vadhan](https://salil.seas.harvard.edu/sites/g/files/omnuum4266/files/salil/files/the_complexity_of_differential_privacy.pdf)

[Exercises for Week 4](exercises/week4.pdf)

**Week 5**: Differentially Private Statistical Estimation, Machine Learning, and Testing

Readings:
* [Abadi et al.](https://arxiv.org/abs/1607.00133)
* [Gaboardi et al.](https://proceedings.mlr.press/v48/rogers16.html)
* [McSherry-Talwar](https://ieeexplore.ieee.org/document/4389483)

[Exercises for Week 5](exercises/week5.pdf)

**Week 6**: Privacy for Distributed Computing

Readings:
* [Warner](https://www.jstor.org/stable/2283137)
* [Kairouz et al.](https://proceedings.mlr.press/v37/kairouz15.html)

[Exercises for Week 6](exercises/week6.pdf)

**Week 7**: Zero-Knowledge Proofs

Readings:
* [Goldwasser-Micali-Rackoff’89](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Proof%20Systems/The_Knowledge_Complexity_Of_Interactive_Proof_Systems.pdf)
* [Goldreich-Micali-Wigderson’86](https://link.springer.com/chapter/10.1007/3-540-47721-7_11)

[Exercises for Week 7](exercises/week7.pdf)

**Week 8**: Statistical Zero-Knowledge Proofs

Readings:
* [Complete Problem for SZK](https://web.cs.ucla.edu/~sahai/work/web/2003%20Publications/J.ACM2003.pdf)
* [Statistical Difference Beyond the Polarizing Regime](https://eccc.weizmann.ac.il/report/2019/038/)

[Exercises for Week 8](exercises/week8.pdf)

**Week 9**: Statistical Zero-Knowledge Proofs with Multiple Verifiers

Readings:
* PRIO: [paper](https://arxiv.org/abs/1703.06255), [application](https://machinelearning.apple.com/research/scenes-differential-privacy)
* Secret Sharing: Chapter 10 of Trappe-Washington

[Exercises for Week 9](exercises/week9.pdf)

**Week 10**: Fully Linear PCPs and Arithmetic Sketching

Readings:
* [Fully Linear PCPs](https://eprint.iacr.org/2019/188.pdf)
* [Arithmetic Sketching](https://eprint.iacr.org/2023/1012)
* PINE: [paper](https://arxiv.org/abs/2311.10237), [IETF](https://datatracker.ietf.org/doc/html/draft-chen-cfrg-vdaf-pine-00)

[Exercises for Week 10](exercises/week10.pdf)

**Week 11**: Multi-Party and Computational Differential Privacy

Readings:
* Chapter 9 and Chapter 10 of [Vadhan](https://salil.seas.harvard.edu/sites/g/files/omnuum4266/files/salil/files/the_complexity_of_differential_privacy.pdf)

[Exercises for Week 11](exercises/week11.pdf)

**Week 12**: Quantum Cryptography

Readings:
* Chapter 1, Chapter 4, Chapter 5 of *Quantum Computation and Quantum Information* by Michael A. Nielsen and Isaac L. Chuang
* Chapter 17 of Trappe-Washington

[Exercises for Week 12](exercises/week12.pdf)

**Week 13**: Information Hiding: Watermarking and Steganography

Readings:
* [Chen and Wornell](https://dl.acm.org/doi/10.1109/18.923725)
* [Moulin and O'Sullivan](https://ieeexplore.ieee.org/document/1184136)
* [Dathathri et al.](https://www.nature.com/articles/s41586-024-08025-4)

[Exercises for Week 13](exercises/week13.pdf)

**Week 14**: Fall Break

**Week 15**: Project Presentations

**Week 16**: Project Presentations and Quiz

## Grading Policy

### Class Participation (30%)

- Attendance is mandatory for all lectures, with a maximum of three unexcused absences allowed.
- Each student must (co)scribe at least one lecture during the course.
- Students must attend final project presentations.

### Exercises (0%)

- There will be weekly (optional) exercises/homework.
- These exercises will not be graded but you can ask the instructor for the solutions.
- The goal is to help you prepare for the quiz and to reinforce your understanding of the material.

### Quiz (10%)

- There will be 1 (in-class) short quiz to gauge students’ understanding of the fundamentals.
- The quiz will take place towards the end of the semester (December 9).
  
### Project (60%)
Students will work on projects related to one or more of the covered topics.
The project is divided into four components:
- Proposal: 15% (October 2)
- Mid-term report: 15% (October 17)
- Final presentation: 15% (December 2, 4, 9)
- Final report: 15% (Dececember 18)
