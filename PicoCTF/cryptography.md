## mod 1
Wrote code to implement the given instructions. Flag: picoCTF{R0UND_N_R0UND_B6B25531}

![mod 1_sol_B](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/c7ab72f3-2218-45db-bb03-a9fed6d6e398)
![mod 1_sol_A](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/f05ddad5-b21d-4808-99e3-2166f6ccfa90)

## miniRSA
RSA encryption keys are generated using the product of two very large prime numbers and an exponent `e`. Encryption is more secure for larger primes and larger values of `e`.
used an online RSA decoder.

flag: picoCTF{n33d_a_lArg3r_e_606ce004}

![miniRSA_sol](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/4190128c-daa7-424d-8f03-371453d7021a)

##  keygenme-py
The given file contains a function that checks for the validity of the key. Once this fact is known, it is only a matter of using the given code to reverse engineer the key, which is the flag we need.

flag: picoCTF{1n_7h3_|<3y_of_01582419}

![keygenme-py_sol_A](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/92b65bea-ad5d-4bc9-9e4e-73a3e8ef8ff3)

This part of the `check_key` function reveals the dynamic part of the key, using which the whole key can be reconstructed thus:

![keygenme-py_sol_B](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/af7b1e07-e2b0-4bc7-ade1-f5c4ab26eb64)






