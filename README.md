# PageRank Algorithm Implementation

This repository contains a Python implementation of the PageRank algorithm, a popular algorithm used to rank web pages based on their importance. The implementation includes graph initialization, computation of PageRank scores, and visualization of the graph with nodes sized proportionally to their PageRank scores.

## Features

- **Graph Initialization**: Creates a sample directed graph using NetworkX.
- **PageRank Computation**: Calculates PageRank scores using a customizable damping factor, maximum iterations, and tolerance for convergence.
- **Graph Visualization**: Displays the graph with node sizes proportional to their PageRank scores using Matplotlib.

## Requirements

The following Python libraries are required:

- `numpy`
- `networkx`
- `matplotlib`

You can install these libraries using the following command:

```bash
pip install numpy networkx matplotlib
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/pagerank-algorithm.git
   cd pagerank-algorithm
   ```

2. Run the script:

   ```bash
   python pagerank.py
   ```

3. The program will:
   - Initialize a sample graph.
   - Compute the PageRank scores for each node.
   - Print the scores to the console.
   - Visualize the graph with nodes sized according to their PageRank scores.


## Sample Output

The program prints the PageRank scores for each node. For example:

```
PageRank Scores:
Node 0: 0.3878
Node 1: 0.1873
Node 2: 0.3524
Node 3: 0.0725
```

The graph visualization will also be displayed, with node sizes reflecting their importance.

## Customization

- **Graph Structure**: Modify the `edges` list in the `initialize_graph` function to change the graph structure.
- **Damping Factor**: Adjust the `damping_factor` parameter in the `compute_pagerank` function to experiment with different levels of importance given to random jumps.
- **Visualization**: Customize node and edge colors, sizes, and layout in the `visualize_graph` function.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

## Contact

For questions or feedback, please reach out to [your email address] or open an issue in this repository.

---

Thank you for exploring this PageRank implementation! Happy coding!

