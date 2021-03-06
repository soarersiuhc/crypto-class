# High School Crypto Class Materials

Materials from teaching cryptography at a 3-week Stanford summer program for high school students (SPCS Summer Institutes, formerly EPGY), with 14 days of instruction from June 23, 2014 to July 10, 2014. The students all just finished 9th or 10th grade.

Almost all of the course material is assembled from scratch, with a focus on math, and a preference to work with actual constructions/numbers instead of full technical proofs (for example, see the mini PRPs in homeworks 11-13).

This sort of course is usually centered around number theory, but I felt that focusing entirely on number theory is a disservice to modern cryptography. Therefore, I focused on interesting/mathematical aspects of block ciphers for the second half of the course.

## Credits

Everything I learned about crypto, I learned from [Dan Boneh](https://crypto.stanford.edu/~dabo/) and the internet.

Almost all the material is based on:

- Dan's [CS255 crypto class at Stanford](https://crypto.stanford.edu/~dabo/cs255/) (which I took once and TAed twice).
- Dan's [Coursera crypto course](https://www.coursera.org/course/crypto) lecture slides.
- Topics discussed in relevant Wikipedia entries.

I also had access to preliminary notes and a syllabus from a previous iteration of the course, taught by [Nick Haber](http://math.stanford.edu/~nhaber/) and based on [`An Introduction to Mathematical Cryptography`](http://link.springer.com/book/10.1007%2F978-0-387-77993-5).

# In this Repository

## Live Code (from class)

- ElGamal Encryption in Mathematica
- Cryptographic Advantage: Coin Game Simulation
- [Block Ciphers](code/Implementations.py)
  - Deterministic CTR (deterministic and randomized),
  - CBC
  - CBC-MAC
  - Authenticated Encryption (CBC with CBC-MAC)
    - Simple key stretching for single-key AE.
 - Encrypting a file on the file system.

In addition to the live code on the computer, I usually went over a concrete example (with small numbers) on the blackboard.

## Homeworks

I created most of these "from scratch".

A few of the problems are taken from CS255.

## Lecture Notes

Not included right now. Everything I have is hand-written on index cards. (It's good for planning out material in board-sized chunks!)

## Syllabus

See [Syllabus.md](./Syllabus.md) for more details.

Here is the major topic for each day:

### Week 1

- Day 1: Introduction
- Day 2: Diffie-Hellman
- Day 3: RSA
- Day 4: ElGamal Encryption
- Day 5: Chinese Remainder Theorem

### Week 2

- Day 6: Birthday Paradox
- Day 7: Perfect Secrecy
- Day 8: More Perfect Secrecy
- Day 9: Semantic Security / Advantage
- Day 10: PRFs, PRPs, and Block Ciphers

### Week 3

- Day 11: More Block Ciphers, CBC-MAC
- Day 12: More CBC-MAC
- Day 13: Hash Functions
- Day 14: Final Day / Extra Topics
