
# Go CLI Utils

A collection of simple and efficient CLI utilities written in Go to streamline everyday tasks. This project provides lightweight commands for generating and validating national codes, as well as generating random UUIDs.

## Features

- **Generate Random National Codes**
- **Validate National Codes**
- **Generate Random UUIDs**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mahdikaseatashin/go-cli-utils.git
   cd go-cli-utils
   ```

2. Build the project:
   ```bash
   go build -o cli-utils
   ```

3. Move the binary to your system's `$PATH` for global use:
   ```bash
   mv cli-utils /usr/local/bin
   ```

## Commands

### 1. `gnc`
Generate a random 10-digit national code.

```bash
cli-utils gnc
```

**Example Output:**
```
0387249941
```

---

### 2. `gnc -r`
Generate a random "round" national code.

```bash
cli-utils gnc -r
```

**Example Output:**
```
5100001100
```

---

### 3. `vnc`
Verify if a given national code is valid.

```bash
cli-utils vnc 0387249941
```

**Example Output:**
```
Valid
```

Or, for invalid codes:

```
Invalid
```

---

### 4. `guuid`
Generate a new random UUID.

```bash
cli-utils guuid
```

**Example Output:**
```
550e8400-e29b-41d4-a716-446655440000
```

## Contribution

Contributions are welcome! Feel free to submit a pull request or open an issue to suggest new features or report bugs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy coding!
