# Lua Table Iteration Bug

This repository demonstrates a potential issue related to table iteration order in Lua.  The `pairs` iterator does not guarantee a specific order, which can lead to unpredictable results when modifying tables during iteration, especially within recursive functions.

The `bug.lua` file contains code that recursively iterates through a nested table. The output might vary depending on the Lua interpreter used.

The `bugSolution.lua` file provides a solution that addresses the issue, offering a reliable approach to recursive table traversal.