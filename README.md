Some benchmarks of different languages
--------------------------------------

The benchmarks follow the criteria:

  - They are written as the average software developer would write them, i.e.

    - The algorithms are implemented as cited in public sources;
    - The libraries are used as described in the tutorials, documentation and examples;
    - Used data structures are idiomatic.

  - The used algorithms are similar between the languages (reference implementations), variants are acceptable if the reference implementation exists.
  - All final binaries are releases (optimized for performance if possible) as debug performance may vary too much depending on the compiler.

# UPDATE 

2019-10-11

# Brainfuck v2.0

Testing brainfuck implementations using two code samples (bench.b and mandel.b).

[Brainfuck v2.0](brainfuck2)
[Brainfuck v1.0](brainfuck)

### bench.b

| Language        | Time, s | Memory, MiB |
| --------------- | ------- | ----------- |
| Kotlin          | 2.01    | 37.6        |
| Nim Gcc         | 2.17    | 0.7         |
| C++ Gcc         | 2.41    | 1.7         |
| Go              | 3.01    | 1.3         |
| Java            | 3.05    | 37.2        |
| Crystal         | 3.06    | 2.7         |
| ML MLton        | 3.22    | 0.7         |
| Go Gcc          | 3.30    | 19.2        |
| Nim Clang       | 3.43    | 1.0         |
| Rust            | 3.51    | 0.8         |
| D Ldc           | 3.57    | 1.4         |
| D Gdc           | 3.72    | 5.8         |
| OCaml           | 3.75    | 3.9         |
| Scala           | 4.30    | 136.3       |
| C# .Net Core    | 4.48    | 23.8        |
| D Dmd           | 4.77    | 1.7         |
| Haskell (MArray)| 6.88    | 3.5         |
| C# Mono         | 6.88    | 17.6        |
| Javascript Node | 7.10    | 31.2        |
| V Gcc           | 7.38    | 0.7         |
| V Clang         | 9.26    | 1.1         |
| LuaJIT          | 10.99   | 2.1         |
| F# Mono         | 12.81   | 25.1        |
| Racket          | 17.52   | 87.4        |
| Python PyPy     | 21.51   | 95.4        |
| Chez Scheme     | 24.72   | 29.2        |
| Haskell         | 29.14   | 3.4         |
| Ruby truffle    | 32.52   | 613.3       |
| Ruby            | 191.36  | 13.1        |
| Ruby JRuby      | 195.63  | 284.4       |
| Lua 5.3         | 201.26  | 1.4         |
| Elixir          | 279.03  | 48.9        |
| Python3         | 396.27  | 7.9         |
| Python          | 399.75  | 6.2         |
| Tcl (FP)        | 494.78  | 4.3         |
| Perl            | 769.17  | 5.2         |
| Tcl (OO)        | 1000.55 | 4.3         |

### mandel.b

[Mandel in Brainfuck](brainfuck2/mandel.b)

| Language        | Time, s | Memory, MiB |
| --------------- | ------- | ----------- |
| C++ Gcc         | 21.42   | 3.5         |
| Crystal         | 22.89   | 2.9         |
| Kotlin          | 27.38   | 44.6        |
| V Gcc           | 27.61   | 2.0         |
| Java            | 28.44   | 43.9        |
| Nim Gcc         | 30.00   | 1.9         |
| Scala           | 30.65   | 139.4       |
| Nim Clang       | 31.39   | 2.4         |
| D Ldc           | 31.56   | 3.7         |
| D Gdc           | 31.87   | 7.2         |
| ML MLton        | 32.04   | 3.6         |
| Go Gcc          | 32.88   | 20.6        |
| Rust            | 33.12   | 1.9         |
| C# .Net Core    | 36.38   | 25.8        |
| V Clang         | 39.26   | 3.0         |
| OCaml           | 44.12   | 7.1         |
| Go              | 45.55   | 2.9         |
| D Dmd           | 56.08   | 4.1         |
| Javascript Node | 69.00   | 34.5        |
| C# Mono         | 71.27   | 18.0        |
| Python PyPy     | 106.44  | 96.2        |
| LuaJIT          | 107.96  | 2.9         |
| Haskell (MArray)| 122.81  | 4.9         |
| Ruby truffle    | 171.47  | 630.7       |
| F# Mono         | 195.99  | 40.0        |
| Racket          | 198.86  | 88.2        |
| Chez Scheme     | 244.82  | 29.3        |

# Base64

Testing large blob base64 encoding/decoding into newly allocated buffers.

[Base64](base64)

| Language        | Time, s | Memory, MiB |
| --------------- | ------- | ----------- |
| C aklomp        | 0.37    | 1.9         |
| C               | 1.86    | 1.8         |
| Rust            | 1.89    | 2.3         |
| Crystal         | 2.32    | 5.3         |
| D Ldc           | 2.44    | 4.0         |
| Ruby            | 2.72    | 72.8        |
| V Gcc           | 2.73    | 1.6         |
| V Clang         | 2.82    | 2.1         |
| D Gdc           | 2.89    | 10.6        |
| Java            | 3.11    | 375.4       |
| Scala           | 3.20    | 154.9       |
| Perl XS         | 3.25    | 6.3         |
| Nim Clang       | 3.27    | 7.4         |
| Kotlin          | 3.29    | 346.0       |
| Nim Gcc         | 3.30    | 7.1         |
| Javascript Node | 3.86    | 100.1       |
| Php             | 3.93    | 16.1        |
| C++ libcrypto   | 4.06    | 5.6         |
| Go              | 4.69    | 13.3        |
| C# .Net Core    | 5.39    | 27.1        |
| D               | 5.74    | 11.2        |
| Tcl             | 6.05    | 5.1         |
| Python          | 6.06    | 7.4         |
| Python PyPy     | 6.22    | 99.9        |
| Python3         | 6.80    | 9.3         |
| Go Gcc          | 7.15    | 43.0        |
| C# Mono         | 8.86    | 36.0        |
| Julia           | 10.84   | 212.8       |
| Ruby JRuby      | 18.51   | 240.4       |
| Perl            | 28.00   | 8.0         |
| Ruby truffle    | 32.39   | 381.7       |

# Json

Testing parsing and simple calculating of values from a big JSON file.

[Json](json)

| Language        | Time, s | Memory, MiB |
| --------------- | ------- | ----------- |
| D Gdc Fast      | 0.30    | 179.8       |
| Rust Pull       | 0.41    | 202.2       |
| Rust Struct     | 0.42    | 222.2       |
| C++ Rapid SAX   | 0.51    | 1.8         |
| C++ Simdjson    | 0.59    | 543.3       |
| C++ Rapid       | 0.86    | 232.6       |
| C++ Gason       | 0.99    | 593.4       |
| Java            | 1.07    | 310.6       |
| Scala           | 1.26    | 227.4       |
| Rust Value      | 2.35    | 1745.8      |
| Crystal Schema  | 2.92    | 283.3       |
| Perl XS         | 2.92    | 941.2       |
| Javascript Node | 3.35    | 517.4       |
| Clojure         | 3.35    | 1472.7      |
| Go              | 4.05    | 512.4       |
| V Gcc           | 4.11    | 1127.4      |
| V Clang         | 4.11    | 1127.8      |
| Python3 ujson   | 4.16    | 1298.5      |
| Php             | 4.25    | 1483.1      |
| Julia           | 4.31    | 2377.6      |
| Crystal         | 5.46    | 961.9       |
| Crystal Pull    | 5.48    | 4.2         |
| C++ LibJson     | 5.65    | 3331.3      |
| Python ujson    | 5.75    | 1454.6      |
| Nim Gcc         | 6.11    | 1321.1      |
| Nim Clang       | 6.18    | 1321.5      |
| Python3         | 6.53    | 979.9       |
| C# .Net Core    | 6.79    | 854.3       |
| Python PyPy     | 6.84    | 1294.9      |
| Go Gcc          | 6.91    | 454.1       |
| D Ldc           | 7.63    | 1546.6      |
| Ruby            | 8.15    | 842.4       |
| Haskell         | 8.24    | 10.0        |
| Ruby Yajl       | 8.63    | 839.7       |
| D Gdc           | 10.16   | 1362.4      |
| Python          | 10.31   | 1465.5      |
| JQ              | 11.58   | 1321.8      |
| C# Mono         | 12.11   | 1046.4      |
| C++ Boost       | 12.45   | 2952.2      |
| Ruby JRuby      | 12.91   | 3090.9      |
| D Dmd           | 14.15   | 1546.7      |
| Perl            | 49.11   | 1212.7      |
| Ruby truffle    | 173.70  | 5276.9      |

# Matmul

Testing allocating and multiplying matrices.

[Matmul](matmul)

| Language        | Time, s | Memory, MiB |
| --------------- | ------- | ----------- |
| Julia Native Thr| 0.11    | 218.6       |
| Julia Native    | 0.29    | 216.2       |
| D lubeck        | 0.38    | 62.8        |
| Python Numpy    | 1.17    | 81.6        |
| D Ldc           | 1.93    | 73.1        |
| D               | 2.16    | 73.1        |
| D Gdc           | 2.28    | 76.7        |
| C               | 3.12    | 69.8        |
| Rust            | 3.17    | 70.7        |
| Nim Clang       | 3.21    | 73.1        |
| Nim Gcc         | 3.23    | 72.4        |
| Julia           | 3.23    | 246.4       |
| Crystal         | 3.33    | 63.1        |
| Go              | 3.36    | 60.2        |
| V Clang         | 3.40    | 70.4        |
| Go Gcc          | 3.41    | 110.7       |
| Kotlin          | 3.43    | 125.9       |
| Java            | 3.81    | 124.7       |
| Scala           | 4.15    | 168.7       |
| V Gcc           | 4.23    | 70.2        |
| Javascript Node | 5.43    | 102.7       |
| C# .Net Core    | 8.21    | 99.3        |
| Python PyPy     | 8.50    | 138.1       |
| Swift           | 8.80    | 205.1       |
| C# Mono         | 14.66   | 88.2        |
| Ruby truffle    | 60.39   | 559.7       |
| Ruby            | 365.68  | 82.5        |
| Ruby JRuby      | 534.93  | 1116.9      |
| Tcl             | 580.68  | 280.5       |
| Python          | 606.50  | 75.7        |
| Perl            | 654.90  | 606.5       |

# Havlak

Testing Havlak's loop finder implementations.

[Havlak](havlak)

| Language        | Time, s | Memory, MiB |
| --------------- | ------- | ----------- |
| Crystal         | 10.70   | 226.4       |
| C++             | 17.23   | 179.2       |
| Nim Gcc         | 17.81   | 506.5       |
| Nim Clang       | 18.46   | 509.9       |
| Go              | 25.34   | 373.6       |
| D Ldc           | 25.86   | 460.4       |
| Scala           | 26.97   | 387.9       |
| D               | 32.09   | 460.2       |
| D Gdc           | 33.26   | 419.0       |
| C# Mono         | 37.37   | 318.8       |
| Go Gcc          | 40.92   | 453.3       |
| C# .Net Core    | 44.02   | 491.4       |
| Python PyPy     | 46.53   | 777.4       |
| Python          | 429.51  | 744.9       |

# Using Docker

Build the image:

    $ docker build docker/ -t benchmarks

Run the image:

    $ docker run -it --rm --name test -v $(pwd):/src benchmarks <cmd>

where <cmd> is:

 - `versions` (print installed language versions)
 - `shell` (start the shell)
 - `brainfuck2 bench` (build and run Brainfuck2 bench.b benchmarks)
 - `brainfuck2 mandel` (build and run Brainfuck2 mandel.b benchmarks)
 - `base64` (build and run Base64 benchmarks)
 - `json` (build and run Json benchmarks)
 - `matmul` (build and run Matmul benchmarks)
 - `havlak` (build and run Havlak benchmarks)

Please note that some tests are unstable under Docker and should be run manually (use `shell` command to get an access to the image).

# Environment

CPU: Intel(R) Core(TM) i7-2600 CPU @ 3.40GHz

OS: Ubuntu 18.04.3 LTS x86_64

| Language     | Version                         |
| ------------ | ------------------------------- |
| .NET Core    | 3.0.100                         |
| C# .NET Core | 3.3.1-beta4-19462-11 (66a912c9) |
| C# Mono      | 6.4.0.198                       |
| Chez Scheme  | 9.5                             |
| Clang        | 7.0.0 (tags/RELEASE_700/final)  |
| Clojure      | "1.10.1"                        |
| Crystal      | 0.31.1                          |
| DMD          | v2.088.1                        |
| Elixir       | 1.9.1                           |
| F#           | 10.2.3 for F# 4.5               |
| GCC          | 9.2.1                           |
| GCC Go       | 9.2.1                           |
| GDC          | 9.2.1                           |
| Go           | go1.13.1                        |
| Haskell      | 8.8.1                           |
| JRuby        | 9.2.8.0                         |
| Java         | 11.0.4                          |
| Julia        | v"1.2.0"                        |
| Kotlin       | 1.3.50                          |
| LDC          | 1.18.0-beta1                    |
| Lua          | Lua 5.3                         |
| LuaJIT       | LuaJIT 2.1.0-beta3              |
| MLton        | 20130715                        |
| Nim          | 1.0.2                           |
| Node.js      | v12.13.0                        |
| OCaml        | 4.07.0                          |
| PHP          | 7.2.19-0ubuntu0.18.04.2         |
| Perl         | v5.26.1                         |
| PyPy         | 7.1.1-final0 for Python 2.7.13  |
| Python 2     | 2.7.15+                         |
| Python 3     | 3.6.8                           |
| Racket       | "6.11"                          |
| Ruby         | 2.6.5p114                       |
| Rust         | 1.38.0                          |
| Scala        | 2.13.1                          |
| Swift        | swift-5.1-RELEASE               |
| Tcl          | 8.6                             |
| TruffleRuby  | 19.2.0.1                        |
| V            | 0.1.21 d4c1bba                  |
| jq           | jq-1.5-1-a5b5cbe                |
| ooc          | 0.9.11-head codename sapporo    |
