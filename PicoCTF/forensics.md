## Macrohard weakedge
After going through the given `.pptm`, it was found that it uses macros. A `.pptm` file is a compressed file that contains all the elements of a presentation and is macro-enabled. 
To inspect the different elements, the file was unzipped. This revealed a file named `hidden` whose contents appeared to be encrypted. 

![macrohard_sol_A](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/d27c25e0-0f26-40dc-87cf-bfe94eb8dda2)
![macrohard_sol_B](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/4e3b0a5d-bcc7-4251-9f94-b6c2c2f66d9c)


The encryption used couldn't have been rot13 or hexadecimal because it contained digits and letters beyond F. The flag was obtained after decryption with `base64 --decode`.

![macrohard_sol_C](https://github.com/mizar-0/Cryptonite-JTP-2/assets/76529146/09260d33-ee56-4050-9094-dca74e4e75a7)

flag: picoCTF{D1d_u_kn0w_ppts_r_z1p5}
