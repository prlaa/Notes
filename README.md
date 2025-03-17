Routing Algorithms

# **1. Greedy Nearest Neighbor Algorithm**
-**What it does:** Starts at a point, always picks the closest unvisited point next, and repeats until all points are visited.
-**Pros:** Simple and fast.
-**Cons:** Doesn’t always give the shortest route because it doesn’t plan ahead.

**2. 2-Opt Heuristic**
-**What it does:** Takes a route and tries to improve it by swapping edges (e.g., if two lines cross, it uncrosses them).
-**Pros:** Better than greedy, often finds shorter routes.
-**Cons:** Slower than greedy but still fast for small datasets.

**3. Genetic Algorithms**
-**What it does:** Mimics evolution. Creates many random routes, keeps the best ones, and mixes them to create new routes.
-**Pros:** Good for large datasets, can find very good routes.
-**Cons:** Complex and slow.

**4. Simulated Annealing**
-**What it does:** Starts with a random route and makes small changes. Sometimes accepts worse routes to avoid getting stuck in bad solutions.
-**Pros:** Can find very good routes, balances exploration and exploitation.
-**Cons:** Slower than greedy, needs tuning.
