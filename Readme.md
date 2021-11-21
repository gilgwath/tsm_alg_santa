# Santa's Stolen Sleigh

## Problem Summary

100000 Christmas gifts have to be delivered from the North Pole to various locations across the Earth while minimizing the Weighted Reindeer Weariness, a metric depending on weight carried and distance travelled.

Distances were to be calculated using the [Haversine Formula which](https://en.wikipedia.org/wiki/Haversine_formula) takes into account the curvature of the Earth's quasi-spherical surface. Each gift had a weight between 1 and 50 (no units specified).
In addition, the sleigh itself had a weight of 10 (same unspecified) and a weight capacity of 1000 (excluding the sleigh base weight).

The problem could be decomposed into two parts:
1. Partition the gifts into trips, where the total weight of gifts to be delivered on any particular trip must satisfy the weight constraint of the sleigh
2. Choose the order in which the gifts should be delivered on each trip.

This problem it is a variation of the Traveling Salesman Problem.