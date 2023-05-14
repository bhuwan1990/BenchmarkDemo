# BenchmarkDemo 
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/your-username/benchmarkdemo/blob/main/LICENSE)

Using [GlobalSetup] attribute, we prepare an array of 100000 randomly chosen integer values between 1 and 100000. This code is executed only once.

## Introduction

The Benchmark Demo project aims to compare the performance of different programming languages by running benchmark tests on common algorithms. It provides an understanding of how different languages handle tasks and helps developers make informed decisions based on performance considerations. We can measure C#, F#, and VB code.

The project currently includes implementations of the following algorithms:

- Sorting algorithms (e.g., bubble sort, selection sort)

Differnent scenario can be test as follows:
- Mathematical algorithms (e.g., Fibonacci series, prime number generation)
- String manipulation algorithms (e.g., string concatenation, string reversal)

## Installation

To run the benchmark demo locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/bhuwan1990/BenchmarkDemo.git
   
$ dotnet add package BenchmarkDotNet
We install the BenchmarkDotNet package.

$ dotnet run --project BenchmarkDemo.csproj -c Release
This is how we run our benchmark.
