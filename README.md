# brute-force-group-15
[![English](https://img.shields.io/badge/en-English-red.svg)](https://github.com/hnthap/brute-force-group-15/blob/master/README.md)
[![Tiếng Việt](https://img.shields.io/badge/vi-Tiếng_Việt-blue.svg)](https://github.com/hnthap/brute-force-group-15/blob/master/README.vi.md)

This is a project for the Algorithm Analysis and Design course. We are Group 
15 and there are presentation slides and some material about Brute Force, the
first part of the Completed Search series.

## Presentation slides

The slides on Brute Force are the file `BRUTE_FORCE.pdf` in this repository.

## Material

You are recommended to read these books and websites above before attending 
class:

* A. Levitin, "Brute Force and Exhaustive Search," in <em>Introduction to the
design & analysis of algorithms</em>, 3rd ed. Boston, Massachusetts, U.S.: 
Addison-Wesley, 2014, ch. 3, pp. 97-130.
* https://www.geeksforgeeks.org/brute-force-approach-and-its-pros-and-cons/
* https://www.youtube.com/watch?v=2WfOUBQYQgA
* The presentation slides provided

Bài toán tìm cặp điểm gần nhất có thể được biểu diễn trong không gian $k$
chiều, trong đó khoảng cách Euclid giữa hai điểm $p'(x'_1, ..., x'_k)$ và
$p''(x''_1, ..., x''_k)$ được định nghĩa là :
$$d(p', p'') = \sqrt{\sum\limits_{s = 1}^k (x'_s - x''_s)^2}.$$
Độ phức tạp thời gian của thuật toán Brute Force cho bài toán tìm cặp điểm gần nhất $k$ chiều là gì ?
