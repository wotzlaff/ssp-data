## Data Description
An instance of the skiving stock problem is given by a threshold length <!-- $L \in \mathbb N$ --> <img src="https://render.githubusercontent.com/render/math?math=L%20%5Cin%20%5Cmathbb%20N"> and a set of item types specified by their length <!-- $l_i$ --> <img src="https://render.githubusercontent.com/render/math?math=l_i"> and frequency <!-- $b_i$ --> <img src="https://render.githubusercontent.com/render/math?math=b_i"> for <!-- $i \in I := \{1, \dots, m\}$ --> <img src="https://render.githubusercontent.com/render/math?math=i%20%5Cin%20I%20%3A%3D%20%5C%7B1%2C%20%5Cdots%2C%20m%5C%7D">.
A set of instances consists of several instances with the same threshold and number of item types.

Each file in the `data` directory contains a particular set of instances.
The format is as follows:
- the first line contains a number which is equal to the number of instances in the set,
- each following line represents an instance written in the form <!-- $L, l_1, \dots, l_m, b_1, \dots, b_m$ --> <img src="https://render.githubusercontent.com/render/math?math=L%2C%20l_1%2C%20%5Cdots%2C%20l_m%2C%20b_1%2C%20%5Cdots%2C%20b_m">, where all values are integers separated by a tab character.

The directories `A1` to `A3` and `B` contain artifical instances generated according to the method described in [[1]](#1).
The set `C` is a collection of benchmark datasets from the literature. Details can also be found in Section 4 of [[1]](#1).

## References
<a id="1">[1]</a>
Martinovic, J., Delorme, M., Iori, M., Scheithauer, G., & Strasdat, N. (2020). Improved flow-based formulations for the skiving stock problem. Computers & Operations Research, 113, 104770.