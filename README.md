def prime_numbers_up_to(n):
    primes = []
    for num in range(2, n + 1):
        for i in range(2, int(num**0.5) + 1):
            if num % i == 0:
                break
        else:
            primes.append(nu)
    return primes

if __name__ == "__main__":
    limit = 50
    print(f"Prime numbers up to {limit}: {prime_numbers_up_to(limit)}")
