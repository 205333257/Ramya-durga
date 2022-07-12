def countPrimeFactors(N):
    count = 0
    prime = [1] * (n + 1)
    for p in range(2, n + 1):
        if p * p > n:
            break
        if (prime[p]):
            for i in range(p * p, n + 1, p):
                prime[i] = 0
    for p in range(2, n + 1):
        if (prime[p]):
            count += 1
    print (count)
n=int(input())
countPrimeFactors(n)
