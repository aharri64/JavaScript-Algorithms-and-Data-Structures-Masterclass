# Section 2: Big O Notation

## Official Intro to Big O

Big O Notation is a way to formalize fuzzy counting numbers

It allows us to talk formally about how the runtime of an algorithm grows as the inputs grow

**We don't care about the details, only the broad trends**

### Big O Definition

```
We say that anm algorithm is O(f(n)) if the number of simple operations the computer has to do is eventually less than a constant times f(n), as n increases
```

- f(n) could be linear (f(n)=n)
- f(n) could be quadratic (f(n)n<sup>2</sup>)
- f(n) could be constant (f(n)=1)
- f(n) could be something entirely different!
