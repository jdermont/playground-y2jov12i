# Introduction

This article is about using genetic algorithm for Search Race optimization game. It's not a tutorial for a complete beginner on genetic algorithms. For that I refer to the [tutorial](https://tech.io/playgrounds/334/genetic-algorithms/history).

# Genetic algorithm

[Genetic algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm) is optimization search inspired by biological evolution. In every generation each candidate solutions (called genomes) are tested and the best ones are selected for reproduction and mutation to the next generation. Over time the solutions improve. This ends when time is up or when good enough solution is found.

Genetic algorithms are commonly used in various puzzles and games on CodinGame. For example in [Mad Pod Racing](http://files.magusgeek.com/csb/csb_en.html) and [Mars Lander](https://www.codingame.com/blog/genetic-algorithm-mars-lander/).

# Search Race

[Search Race](https://www.codingame.com/multiplayer/optimization/search-race) is an optimization game in which our car has to pass checkpoints as quickly as possible. Sometimes I refer to it as single player Mad Pod Racing. At time of writing this article, I'm 6th on the leadeboard. My solution is based of course on genetic algorithm.

