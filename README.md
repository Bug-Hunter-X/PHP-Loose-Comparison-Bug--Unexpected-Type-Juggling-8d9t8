# PHP Loose Comparison Bug

This repository demonstrates a common, yet subtle, bug in PHP related to loose comparisons.  The code showcases how PHP's type juggling can lead to unexpected results when using the `==` operator.

The `bug.php` file contains the erroneous code, while `bugSolution.php` provides the corrected version using strict comparison (`===`).  Always favor strict comparison to ensure type safety and prevent unexpected behavior.