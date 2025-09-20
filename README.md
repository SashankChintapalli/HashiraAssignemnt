# Hashira Polynomial

This project computes a polynomial from given roots expressed in arbitrary bases.
It supports input via a JSON file, converts all roots to decimal, constructs the polynomial, and prints both:

1. The **expanded polynomial**
2. The list of **coefficients**
3. The **constant term `c`**

---

## 📂 Input Format

The input is provided as a JSON file (`input.json`). Example:

```json
{
  "keys": {
    "n": 4,
    "k": 3
  },
  "1": { "base": "10", "value": "4" },
  "2": { "base": "2", "value": "111" },
  "3": { "base": "10", "value": "12" },
  "6": { "base": "4", "value": "213" }
}
```

* `n`: total number of roots availab
