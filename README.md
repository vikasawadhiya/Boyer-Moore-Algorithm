# Boyer-Moore Algorithm

<p align="justify">The Boyer-Moore algorithm is an efficient string searching algorithm. To search a pattern 
in a string, algorithm pre-processes the pattern and as a result creates two tables the delta<sub>1</sub> table 
and the delta<sub>2</sub> table. These tables help the algorithm to slide the pattern to the right as 
far as possible (which can be less than or equal to the pattern length) in case of 
a character mismatch as compared to the naïve algorithm which always slides the pattern to the 
right direction by one position in case of a character mismatch. It performs 
the character matching from right to left, which means it begins the pattern matching 
from the last character of the patter and move toward the first character of the pattern as matches succeed.</p>

<p align="justify">The Boyer-Moore algorithm has linear time complexity in average case scenario, quadratic time complexity in worst 
case scenario which is rare in practice and performs better than linear time complexity 
in best case scenario as compared to the naïve algorithm of quadratic time complexity.</p>

## Tutorial Document

<p align="justify">The tutorial document <a href="https://github.com/vikasawadhiya/Boyer-Moore-Algorithm/blob/main/BoyerMooreAlgorithm.pdf">BoyerMooreAlgorithm.pdf</a>
explains the algorithm in detail. It is a <b>One Time Read</b> document that explains the 
Boyer-Moore algorithm in such detail and in the simplest manner that only a single 
reading of this document is required to understand the concept. It uses a lot pictorial 
representations, mostly tables, to present the concept in an illustrative manner.</p>

<p align="justify">The tutorial document begins by explaining the different categories or scenarios of a character 
mismatch and then explains the delta<sub>1</sub> table and the delta<sub>2</sub> table creation which is 
a most crucial part of algorithm and then shows the usage of both of these tables in a complete example.</p>