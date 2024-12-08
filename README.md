# Haskell Sort Function: Unexpected Behaviour with Incomparable Types

This repository demonstrates a potential issue with the `sort` function in Haskell when dealing with lists containing incomparable types.  The `sort` function relies on the `Ord` type class, and if the elements in the list don't have a consistent ordering defined, unexpected results or runtime errors can occur.

The `bug.hs` file contains a simple example that works correctly. The `bugSolution.hs` shows a more robust approach.