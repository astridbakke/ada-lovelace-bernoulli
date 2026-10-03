# Ada Lovelace's "Note G" 

This notebook explores the historical significance of **Ada Lovelace's "Note G"**, written in 1843 for Charles Babbage’s mechanical Analytical Engine and widely recognized as the world's first published computer program.

Rather than relying on modern recursive functions, this project translates her historical operational table into a modern executable table using Python. It emulates the machine's 25 physical register columns step-by-step to show how the logic actually executed under the hood.

## Overview
* **Target:** Computing Bernoulli numbers (specifically targeting $B_8$) using Lovelace's original sequence of operations.
* **Implementation:** Uses a 25-element Python array (`V`) to mimic the mechanical register columns of the Analytical Engine.
* **Historical Nuance:** Includes the correction for the famous division order bug present in the original 1843 publication table.

## Project Structure
* `bernoulli-noteG.ipynb`: The core Jupyter Notebook containing the interactive register emulation and background notes.

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
