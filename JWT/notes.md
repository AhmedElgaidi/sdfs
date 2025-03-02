## Test for:
1) Accepting arbitrary signatures.
2) Accepting tokens with no signature.
3) Brute-forcing weak secret keys with hashcat.
4) Injecting self-signed JWTs via "JWK" parameter.
5) Injecting self-signed JWTs via "jku" parameter.
6) Injecting self-signed JWTs via "kid" parameter.
7) Algorithm Confusion Attack (Exposed public key).
8) Algorithm Confusion Attack (Deriving public key from existing tokens).


### **[Note]:**
Look at the token algorithm type in the jwt data (symmetric, asymmetric) in order to perform **"Algorithm Confusion Attack"**.