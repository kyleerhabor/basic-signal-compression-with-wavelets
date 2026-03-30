# Basic Signal Compression with Wavelets

A program to apply the 1D discrete Haar transform to a numeric signal, zeroing-out all detail coeﬃcients below a certain threshold and applying the inverse transform to demonstrate basic data compression.

```sh
clojure -M -m kyleerhabor.basic-signal-compression-with-wavelets.core -s 4 -s 6 -s 10 -s 12 -s 8 -s 6 -s 2 -s 2
clojure -M -m kyleerhabor.basic-signal-compression-with-wavelets.core -s 4 -s 6 -s 10 -s 12 -s 8 -s 6 -s 2 -s 2 -t 1.42 # √2
```
