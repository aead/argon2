[![Godoc Reference](https://godoc.org/github.com/aead/argon2?status.svg)](https://godoc.org/github.com/aead/argon2)

## The Argon2 password hashing algorithm

Argon2 is a memory-hard password hashing function and was selected as the winner of the Password Hashing Competition.
Argon2 can be used to derive high-entropy secret keys from low-entropy passwords and is specified at
https://github.com/P-H-C/phc-winner-argon2/blob/master/argon2-specs.pdf 

### Recommendation 
This Argon2 implementation was submitted to the golang x/crypto repo.
I recommend to use the official [x/crypto/argon2](https://godoc.org/golang.org/x/crypto/argon2) package if possible.  
**Currently the x/crypto implementation contains a bug which is already fixed here and also pushed upstream.**

### Installation

Install in your GOPATH: `go get -u github.com/aead/argon2`