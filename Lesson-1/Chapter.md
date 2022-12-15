## Chapter 1

```
pragma solidity >=0.5.0 <0.6.0;

 contract  ZombieFactory {

 }


```

## Chapter 2

```
pragma solidity >=0.5.0 <0.6.0;

contract ZombieFactory {

    uint dnaDigits = 16;

}
```

## Chapter 4

```
pragma solidity >=0.5.0 <0.6.0;

contract ZombieFactory {

    uint dnaDigits = 16;
    uint dnaModulus = 10**dnaDigits;

}
```

## Chapter 5

```
pragma solidity >=0.5.0 <0.6.0;

contract ZombieFactory {

    uint dnaDigits = 16;
    uint dnaModulus = 10 ** dnaDigits;

    struct Zombie {
        string name;
        uint dna;
    }

}
```
