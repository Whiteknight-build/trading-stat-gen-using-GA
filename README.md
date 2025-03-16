# trading-stat-gen-using-GA
building a genetic algorithm with the ability to create functional strategies

# Fundamentals
Initialization: Generate a diverse population of random trading strategies.
Evaluation: Backtest each strategy and assign fitness scores based on performance metrics.
Selection: Choose the best-performing strategies to become parents for the next generation.
Crossover: Combine parameters from parent strategies to create offspring.
Mutation: Randomly alter some strategy parameters to maintain genetic diversity.
Replacement: Form a new population from offspring and elite parents.

# Genes 
parameters are encoded as chromosomes containing:
Entry / Exit rules based on techinical indicators and price action 
take profit % 
stop loss 

# Performance metrics
 returns
 loss:winns ratio
 minimizing drawdown
 profits

since the equity market is so large we have divided the stocks into sectors , and the equity time seires into regimes and seprate strategies will be created for each regime.

