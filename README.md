# RSA Factoring Challenge

This repository contains a solution for the RSA Factoring Challenge, which involves factorizing RSA numbers into their prime factors.

## Background

RSA (Rivest–Shamir–Adleman) is one of the first public-key cryptosystems and is widely used for secure data transmission. The security of RSA relies on the difficulty of factoring large composite numbers into their prime factors.

The RSA Factoring Challenge aims to factorize RSA numbers (composite numbers used in RSA encryption) into their two prime factors. This task is crucial for understanding the security of RSA encryption and for breaking RSA-encrypted data.

## Task Description

The RSA Factoring Challenge involves writing a script to factorize RSA numbers provided in files into their two prime factors. The script should be optimized to complete within a time limit of 5 seconds. The factors produced by the script should always be prime numbers.

## Files

- `rsa`: The script for factorizing RSA numbers.
- `tests/`: Directory containing input files for testing the `rsa` script.

## Usage

To run the script, use the following command:
./rsa <input_file>

Replace `<input_file>` with the path to a file containing an RSA number to factorize.

## Example

```bash
$ cat tests/rsa-1
6
$ ./rsa tests/rsa-1
6=3*2
