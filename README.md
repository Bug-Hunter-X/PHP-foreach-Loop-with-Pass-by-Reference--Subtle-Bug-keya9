This repository demonstrates a subtle bug in PHP related to pass-by-reference in `foreach` loops. The `bug.php` file contains the erroneous code, while `bugSolution.php` offers a corrected version.  The issue arises from how PHP handles references within the loop, potentially leading to unexpected modifications outside the loop's scope. The solution showcases safer ways to manage references when iterating and modifying arrays.