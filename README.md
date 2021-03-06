# Guess Digits Sum game

Can you guess the sum of K digits fast enough?

## Given

Let `number` be K digits distributed uniformly (K=4: `numbers` are 0000, 0001, ..., 9998, 9999).  
Let `n` be the sum of digits in the `number` (K=6: n(098706)=30).  
Let `guess` be a single attempt to guess `n`. If you miss, you get a hint if your guess is too high (`guess > n`) or too low (`guess < n`).

## Required

The Solution (the algorithm) which finds `n` in the least number of `guess` attempts.

## Questions (in order of complexity)

### 1. A, B, C

With *The Solution* and `K = 4`, tell the sequence of guesses leading to the right answer.

### 2. Total number of guesses for K = 8

Assuming `g(n)` is the number of guesses it takes your algorithm to find the answer for number `n`,
find the average number of guesses in `K = 8` range (`00000000` to `99999999`). To find this, simply
sum `g(n)` for all numbers in range and divide by their count.

Example answer: total number of guesses is 423297777 or about 4.2 guesses on average.

### 3. Total number of guesses for K = 16, 20

Having *The Well Coded Solution*, provide **Question 2** answer for `K = 16` and `K = 20`.

Example answers:
- `K = 16`, number of guesses is 46763514977777777 or about 4.6 `guesses` on average
- `K = 20`, number of guesses is 484743581777777777777 or about 4.8 `guesses` on average

### 4. O(K) *

Find *Computational complexity* in big O notation for *The Solution*.

`*` I don't know the answer, maybe you do :)

## Don't read this

Some stuff is available by

    $ ruby g_sum.rb 6

*The Well Coded Solution* will be provided after the contest.
