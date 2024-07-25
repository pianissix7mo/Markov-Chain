The provided document is a project report on a Markov Chain Model for Casino Profit Maximization. The key points from the document are:

### Title and Authors
- Title: Markov Chain Model for Casino Profit Maximization
- Authors: Shaoyi Li, Pedro Duarte Moreira, Astrid Zhao, Mofei Wang

### Abstract
The report proposes a model to determine the optimal slot machine winning rate for maximizing casino profits using a Markov chain model based on the Gambler’s Ruin concept. Both analytical solutions and Monte Carlo simulations were employed to visualize and compute the optimal winning rates under various scenarios.

### Key Sections
1. **Introduction**
   - Focus on games of chance, particularly slot machines, which are significant earners for casinos.
   - Use of a Markov chain model to analyze and optimize the gambler's winning rates.

2. **Model**
   - **General Assumptions**
     - Simplifies slot machine outcomes to either win or lose $1.00.
     - Casinos control the probability of winning or losing.
     - Players play until they lose all tokens or win a certain amount.
   - **General Model**
     - A Markov chain with states representing the number of tokens a gambler has.
     - Idle states for when gamblers temporarily stop playing after winning or losing.
   - **Default Parameter Values**
     - Example values: max_money is 6, start_money is 2, n_gamblers is 5000, and n_steps is 240.
     - Casino's control over the winning probability \( p \) and its impact on profit.

3. **Analysis**
   - **Sensitivity Analysis**
     - Explores how varying \( p \), \( q_{lose\_ratio} \), \( q_{win} \), and start_money affects profit.
     - Optimal \( p \) values range between 0.15 and 0.35 for maximum profit.
   - **Extension: Analytical Solution**
     - Derives the expected total profit per gambler analytically.
     - Verifies the analytical solution against Monte Carlo simulation results.

4. **Discussion**
   - Summarizes findings, emphasizing the balance needed for the optimal winning probability to ensure profitability.
   - Highlights the trade-offs between computational complexity and practical implementation of simulations.

### Appendices
- Detailed mathematical derivations and additional scenario analyses.

This summary captures the essence and key findings of the report, focusing on the mathematical modeling and sensitivity analysis used to determine the optimal winning rates for slot machines in casinos.
