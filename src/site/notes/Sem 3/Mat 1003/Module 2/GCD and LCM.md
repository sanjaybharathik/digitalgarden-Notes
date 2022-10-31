---
{"dg-publish":true,"permalink":"/sem-3/mat-1003/module-2/gcd-and-lcm/"}
---


up: [[Sem 3/Mat 1003/1003 Module 2|1003 Module 2]]
tag: #dms/module2 

# GCD and LCM
## GCD (Greatest Common Divisor)

-> AKA HCF (Higest Common Factor)
-> gcd(a,b)

int a and b are relatively prime if gcd(a,b) = 1.

let a and b be posive integers with p1,p2.....pn prime factor from prime factorization, so that 

a = p1^a1 .p2^a2.....pn^an
b = p1^b1 .p2^b2.....pn^bn

Where ai,bi >= 0 for 1 <= i <= n

#### gcd(a,b)=p1^min(a1,b1).p2^min(a2,b2)........pn^min(an,bn)

## LCM (Least Common Multiple)

#### lcm(a,b)=p1^max(a1,b1).p2^max(a2,b2)........pn^max(an,bn)

## ab = gcd(a,b)* lcm(a,b)