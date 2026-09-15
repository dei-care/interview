# problem-solving

C++17 **competitive-programming** archive — algorithm templates plus accepted contest solutions.

## Layout

| Path | Role |
| --- | --- |
| [`src/coding/reference/`](src/coding/reference/) | Handbook-style templates (graphs, DP, strings, math, data structures) |
| [`src/coding/solved/`](src/coding/solved/) | Accepted solutions by platform (`{platform}/{slug}.cpp`) |

## Quick start

```bash
# Compile every .cpp under src/coding/
./.github/scripts/compile-coding.sh

# Single file
g++ -std=c++17 -O2 -Wall src/coding/reference/graphs/shortest-path.cpp
```

Format: `clang-format -i src/coding/**/*.cpp`
