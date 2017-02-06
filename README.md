### TakeMeTour Internship Program 2017

Hi all applicants! Welcome to TakeMeTour Internship Program 2017. Being and intern at TakeMeTour is challenging so we have challenges for you! These challenges are designed to assess your learning skill, which is the fundamental and most important skill of great software developer. So I do not expect you to have full or any knowledge about the topic beforehand but it's your job to try to learn and answer those challenges.

## Haskell

Haskell is a functional programming language. The fundamental concept is totally different to the traditional (imparative) language.
1. Please write a function that check if the input number is prime number. For example,
```
> is_prime 5
True
> is_prime 4
False
```
Answer:
```
factors n = [x | x <- [1..n], n `mod` x == 0]
is_prime n = factors n == [1, n]
```
2. Please write a function that calculate nth number of fibonacci sequence. For example,
```
> fibo 1
0
> fibo 5
3
```
Answer:
```
fibo :: Int -> Integer
fibo = (map fib[0..]!!)
  where fib 0 = 0
        fib 1 = 0
        fib 2 = 1
        fib n = fibo(n-2) + fibo(n-1)
```

## Questions
Q1: What is GraphQL and how it is different from REST API?

A1: GraphQL Query is a string interpreted by a server that returns data in a specified format. GraphQL supports by any appication and REST API need to specify database before use.


Q2: Please explain how javascript benefits from cross-platform development

A2: Java can run any platform by only download javascript. That means create on my computer can run in other computer.


Q3: What do you expect to get from during an internship at TakeMeTour?

A3: cooperation with a team, responsibility in my work, real life working, experience


## Submitting

Please fork this repo and submit your repository at panj@takemetour.com along with your contact information.

Note: These challenges must be done by yourself. There is no benefit for both sides if the answer do not reflect your true skill.
