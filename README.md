# array_manipulation

Starting with a 1-indexed array of zeros and a list of operations, for each operation add a value to each array element between two given indices, inclusive. Once all operations have been performed, return the maximum value in the array.

## Function Description

Complete the `array_manipulation` function which has the following parameters:

* `int n`: the number of elements in the array
* `int queries[q][3]`: a two dimensional array of queries where each `queries[i]` contains three integers, `a`, `b`, and `k`.

Returns

* int: the maximum value in the resultant array

## Input Format

The first line contains two space-separated integers `n` and `q`, the size of the array and the number of queries.

Each of the next `q` lines contains three space-separated integers `a`, `b`, and `k` -- the left index, right index, and number to add.

## Constraints

* 3 <= n <= 10^7
* 1 <= m <= 2 * 10^5
* 1 <= a <= b <= n
* 0 <= k <= 10^9
