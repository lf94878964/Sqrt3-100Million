# √3 (Square Root of 3) Digit Files

This repository contains plain text files with the value of √3 (the square root of 3) truncated to different numbers of decimal places. Each file starts with `1.` followed by the digits after the decimal point (no extra whitespace or trailing newline).

## Files

| File                   | Decimal digits | File size          |
| ---------------------- | --------------- | ------------------- |
| `sqrt3_10.txt`         | 10               | 12 bytes             |
| `sqrt3_100.txt`        | 100              | 102 bytes            |
| `sqrt3_1000.txt`       | 1,000            | 1,002 bytes          |
| `sqrt3_10000.txt`      | 10,000           | 10,002 bytes         |
| `sqrt3_100000.txt`     | 100,000          | 100,002 bytes        |
| `sqrt3_1000000.txt`    | 1,000,000        | 1,000,002 bytes      |
| `sqrt3_10000000.txt`   | 10,000,000       | 10,000,002 bytes     |
| `sqrt3_50000000.txt`   | 50,000,000       | 50,000,002 bytes     |
| `sqrt3_100000000.7z`   | 100,000,000      | 100,000,002 bytes (uncompressed) |

> The `sqrt3_100000000.7z` archive needs to be decompressed.

## Example

`sqrt3_10.txt`:

```
1.7320508075
```

## Format

Each file follows the pattern:

```
1.<N digits of √3>
```

where `<N digits of √3>` is the first N digits of √3 after the decimal point.

## Source

Digits were truncated from a 160,000,000-decimal-digit reference file of √3 (only the first 100,000,000 digits are provided here).

## About

This project allows you to download a plain text file containing √3 (the square root of 3) to 100 million decimal places.
