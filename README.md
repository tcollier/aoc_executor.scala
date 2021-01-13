# AoC Scala Executor

Scala executor for the [Advent of Code Solver](https://github.com/tcollier/aoc_solver).

## Template Code

```scala
import tcollier.Executor;
import tcollier.Solution;

class Day1Solution() extends Solution {
  def part1Answer(): String = {
    // compute part 1 solution
    return solution
  }

  def part2Answer(): String = {
    // compute part 2 solution
    return solution
  }
}

object Main {
  def main(args: Array[String]): Unit = {
    val input: Array[String] = // load input
    val executor: Executor = new Executor(new Day0Solution(input), input);
    executor.run(args);
  }
}
```
