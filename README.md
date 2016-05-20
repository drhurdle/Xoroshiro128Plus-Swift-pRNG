# Xoroshiro128Plus-Swift-pRNG
Pseudo-Random Number generator utilizing xoroshiro128+ algorithm in Swift 2.2


Iniitalize the pRNG
```sh
var rng = PRNG()
```

When initializing you can opt to enter a seed of your choice 
```sh
var rng = PRNG(seed: 87364965)
```

To get random numbers from the generator, simply call 
```sh
// Returns a random number between 0 and 18,446,744,073,709,551,615
rng.getRandomNumber()

// Returns a random number between 0 and 100
rng.getRandomNumber(max: 100)

// Returns a random number between 10 and 20
rng.getRandomNumber(10, max: 20)
```
