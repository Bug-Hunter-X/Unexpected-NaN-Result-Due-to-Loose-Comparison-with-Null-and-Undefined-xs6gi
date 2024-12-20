# Unexpected NaN Result Due to Loose Comparison with Null and Undefined

This code demonstrates a common JavaScript error resulting from loose comparison (==) between null and undefined. The function `foo` is designed to return 0 when the input is null; however, it produces NaN when given undefined because of the loose comparison failing to distinguish between them.  The solution shows how to use strict equality (===) to solve this problem.
