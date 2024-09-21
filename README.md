This project solves The Bakery Problem, where we rank five bakeries based on the probability of receiving good bread. Using probabilistic models, we aim to optimize daily bakery choices.

Approaches
N-Test Selection: Each bakery is tested a fixed number of times, and the best one is selected for future purchases.
Beta Distribution Strategy (Primary Approach): This method applies Thompson Sampling to update the probability of success for each bakery dynamically.
Greedy Exploration: Combines exploration of new bakeries with exploitation of those known to give better results.
Results
Through 10,000 simulated runs over one year, the Beta Distribution Strategy produced a 76.1% satisfaction rate, making it the most effective approach compared to the others.
