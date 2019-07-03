# LWE-KEM_MatProd
Post Quantum Learning With Errors Problem Based Key Encapsulation Protocols and Matrix Vector Product


Only matrix vector multiplication has been changed in Lizard software.
The mat_mul.h and mat_mul.c files have been added to the software. Files other than these files are from the Lizard software's NIST site. Which can be found in:
https://csrc.nist.gov/CSRC/media/Projects/Post-Quantum-Cryptography/documents/round-1/submissions/Lizard.zip

Added two files are modified versions of the matrix vector multiplication operations in the [FrodoKEM](https://frodokem.org/) protocol.
Changes within the Lizard protocol have been made in the Lizard.c file.

In the same directory, you can compile the software with just typing make command. This command would generate a single executable, which can be runned as ./Lizard.
