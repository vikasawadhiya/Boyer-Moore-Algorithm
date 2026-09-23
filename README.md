# Boyer-Moore Algorithm

<p align="justify">The $Boyer-Moore$ algorithm is an efficient string searching algorithm. To search a pattern 
in a string, algorithm pre-processes the pattern and as a result creates $delta_1$ & $delta_2$ tables. 
These tables help the algorithm to slide the pattern to the right as far as possible (which can be less than 
or equals to the pattern length) in case of a character mismatch, as compared to the naive algorithm which 
always slides the pattern one position to the right in case of a character mismatch. It performs the character 
matching from right to left, which means it begins the pattern matching from the last character of the patter 
and move toward the first character of the pattern as matches succeed.
</p>

<p align="justify">The $Boyer-Moore$ algorithm has linear time complexity in average case scenario, quadratic time 
complexity in worst case scenario which is rare in practice and performs better than linear time complexity 
in best case scenario as compared to the naive algorithm of quadratic time complexity.
</p>

## Tutorial Document

<p align="justify">The tutorial document <a href="https://github.com/vikasawadhiya/Boyer-Moore-Algorithm/blob/main/BoyerMooreAlgorithm.pdf">BoyerMooreAlgorithm.pdf</a>
explains the algorithm in detail. It is a <b>One Time Read</b> document that explains the $Boyer-Moore$ algorithm in 
such a detail and in a simplest manner that only a single reading of this document is required to understand the concept.
</p>

<p align="justify">The tutorial document begins by explaining the different categories or scenarios of a character 
mismatch and then explains how the $delta_1$ & $delta_2$ tables are created, which is a most crucial part of algorithm 
and then shows the usage of both of these tables in a complete example.
</p>

## Example

<p align="justify">
Let's consider a pattern, $\mathbf{Patt} = \mathbf{"abcdabcab"}$ as an example then algorithm creates $delta_1$ & $delta_2$ tables as shown below,
</p>

<p align="center">
<img src="https://github.com/vikasawadhiya/Boyer-Moore-Algorithm/blob/main/patternAndTables.svg" alt="Delta1 and Delta2 tables of the patter 'abcdabcab'.">
</p>