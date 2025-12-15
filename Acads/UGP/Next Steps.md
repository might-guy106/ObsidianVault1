### Scripts
- scripts for 2 phase mode: the scripts should divide preprocessing and online mode where change in latency should not affect the onine mode 
- complete rest of the scripts

### Other
- formulate additve shares to Xor shares mpc protocol
- instead of a Doram for sibling we can simple use an array. as the data inside need not be anonymous as it is public information that who is whose sibling just. to implement this we need to solve below ponts
	- how to convert or represent additive shares of index as standard basis vector where it sums up to only 1 at that required index
	- how to do dot product between these standard basis vector and the sibling vector. is it simply element wise multiplcation and aggregating all of these using a for loop ?