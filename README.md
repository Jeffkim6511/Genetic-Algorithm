# 🧬 Genetic Algorithm

This project implements a **Genetic Algorithm** that evolves a population of lists, where each list contains 8 integers with values ranging from **1 to 4**. The algorithm runs for a user-defined number of generations (cycles), applying the principles of selection, crossover, and mutation to converge toward an optimal solution. This was created to explore the relationship between biology and machine learning models.

## 📂 Files

- 'GeneticAlgorithm.ipynb` – Main Jupyter notebook containing the full implementation of the genetic algorithm.

## ⚙️ How It Works

1. **Initialization**  
   A population of individuals is randomly generated. Each individual is a list of 8 integers where each value is between 1 and 4.

2. **Fitness Evaluation**  
   A fitness function evaluates how "fit" or close to the desired outcome each individual is. The closer to the ideal configuration, the higher the score.

3. **Selection**  
   Individuals are selected based on their fitness scores. Fitter individuals have a higher probability of being selected as parents.

4. **Crossover**  
   Selected parents produce offspring via crossover, combining traits from both parents to create a new generation.

5. **Mutation**  
   Random mutations are introduced to maintain genetic diversity by changing values in the list with a small probability.

6. **Cycle Iteration**  
   The process repeats for a number of cycles (generations) specified by the user.

## 🛠️ How to Run

1. Open the notebook in JupyterLab or Jupyter Notebook.
2. Run each cell in order.
3. When prompted, input the number of generations (cycles) you want the algorithm to run.

## 📈 Example Output

After running the algorithm, you'll see how the population evolves over time, ultimately converging toward an optimal or near-optimal list configuration.

## 🧪 Dependencies

- Python 3.x
- No external libraries required (uses built-in Python functions)

## 📚 Notes

- You can modify the mutation rate, population size, or fitness function to experiment with different evolutionary behaviors.
- The algorithm is flexible and can be adapted to other problem spaces by changing the individual structure or fitness function.
- Biological processes like Miosis and natural selection seem to provide viable strategies for machine learning. However, alot of evolution is still based on chance. Therefore, adding an external factor to mediate which traits are desired could prove to be more useful in machine learning.
