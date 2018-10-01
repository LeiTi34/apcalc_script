# Binomialfunktionen
### C(n,k)
$$ C(n,k) = \binom{n}{k}$$

### Cvert(n,k,p)
$$ Cvert(n,k,p) = \binom{n}{k} \cdot p^k \cdot (1-p)^{n-k}$$

### Cvertsum(n,k,k0,p)
$$ Cvertsum(n,k,k0,p) = \sum\nolimits_{k=k0}^k\binom{n}{k} \cdot p^k \cdot (1-p)^{n-k}$$

# Hypergeometrische Funktionen
### H(M, N, n, k)
$$H(M, N, n, k) = \frac{\binom{M}{k}\binom{N - M}{n - k}}{\binom{N}{n}}$$

### Hsum(M,N,n,k,k0)
$$Hsum(M,N,n,k,k0) = \sum\nolimits_{k=k0}^k\frac{\binom{M}{k}\binom{N - M}{n - k}}{\binom{N}{n}}$$
