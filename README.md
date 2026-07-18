# Matplotlib Assignment

A comprehensive learning project focused on mastering data visualization and creating compelling visual representations using the Python Matplotlib library.

## 📋 Overview

This repository contains practical exercises and assignments designed to build proficiency with Matplotlib, the foundational library for data visualization in Python. The project covers fundamental to advanced concepts through hands-on Jupyter notebooks and real-world visualization scenarios that are essential for data science and exploratory data analysis.

## 🎯 Objectives

- Master Matplotlib plotting and visualization fundamentals
- Develop skills in creating various chart types and plots
- Learn customization and styling techniques for visualizations
- Practice exploratory data analysis (EDA) with visual representations
- Understand figure, axes, and subplot management
- Apply Matplotlib to real-world datasets and visualization challenges

## 📁 Repository Structure

```
matplotlib-assignment/
├── README.md                    # Project documentation
├── matplotlib-practice.ipynb    # Main Jupyter notebook with exercises
├── environment.yml              # Conda environment configuration
├── data/                        # Directory for datasets
└── .gitignore                   # Git ignore rules
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Conda or pip package manager
- Jupyter Notebook

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/learner-Piyush/matplotlib-assignment.git
   cd matplotlib-assignment
   ```

2. **Create the Conda environment:**

   **Option 1: Local environment (Recommended)** ⭐
   
   Create the environment in a local `./env` directory within your project:
   ```bash
   conda env create -f environment.yml --prefix ./env
   ```
   
   **Option 2: Named environment (System-wide)**
   
   Create the environment in Conda's default directory:
   ```bash
   conda env create -f environment.yml
   ```

3. **Activate the environment:**

   **For Option 1 (local):**
   ```bash
   conda activate ./env
   ```
   
   **For Option 2 (named):**
   ```bash
   conda activate matplotlib-assignment
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. **Open `matplotlib-practice.ipynb` in your browser and start exploring!**

### Deactivating the Environment

When you're done, deactivate the environment with:
```bash
conda deactivate
```

### Cleaning Up (Local Environment Only)

If you created the environment with `--prefix ./env`, you can remove it by simply deleting the folder:
```bash
rm -rf ./env
```

## 📚 Contents

### `matplotlib-practice.ipynb`
The main interactive notebook containing:
- Matplotlib fundamentals (figures, axes, and subplots)
- Basic plotting (line plots, scatter plots, bar charts)
- Histogram and distribution visualizations
- Box plots and violin plots
- Multi-subplot layouts and complex figures
- Customization and styling (colors, markers, line styles)
- Labels, titles, legends, and annotations
- Saving and exporting visualizations
- Creating publication-quality figures
- Practice exercises and visualization challenges

### `environment.yml`
Conda environment file specifying all required dependencies including:
- matplotlib
- jupyter
- numpy
- pandas
- scipy
- seaborn
- And other supporting libraries

## 🛠️ Technologies Used

- **Python 3** - Programming language
- **Matplotlib** - Data visualization and plotting
- **Jupyter Notebook** - Interactive computing environment
- **Conda** - Environment management

## 📖 Learning Path

1. Start with Matplotlib fundamentals (figures and axes)
2. Progress to basic plot types and visualizations
3. Explore customization and styling techniques
4. Learn multi-subplot layouts and complex figures
5. Practice creating publication-quality visualizations
6. Apply techniques to real-world datasets

## 💡 Tips for Learning

- Execute each cell in the notebook sequentially
- Modify the code examples to experiment with different approaches
- Try creating visualizations with your own datasets
- Refer to [official Matplotlib documentation](https://matplotlib.org/stable/contents.html) for detailed information
- Practice consistently to solidify your understanding
- Explore the gallery for inspiration and examples

## 📊 Key Matplotlib Concepts Covered

- Creating figures and axes using object-oriented interface
- Basic plot types (line, scatter, bar, histogram, box, violin)
- Figure layout and subplot management (subplots, GridSpec)
- Customization (colors, markers, line styles, fonts)
- Labels, titles, legends, and text annotations
- Axes formatting and styling
- Multiple axes and complex figure layouts
- Saving and exporting figures in multiple formats
- Interactive features and event handling
- Creating publication-quality visualizations

## 🤝 Contributing

This is a personal learning project. However, if you have suggestions or improvements, feel free to open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or feedback, please contact [learner-Piyush](https://github.com/learner-Piyush).

## 🔗 Useful Resources

- [Matplotlib Official Documentation](https://matplotlib.org/stable/contents.html)
- [Matplotlib User Guide](https://matplotlib.org/stable/users/index.html)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/index.html)
- [Real Python Matplotlib Tutorials](https://realpython.com/python-matplotlib-guide/)
- [Matplotlib Cheat Sheet](https://github.com/matplotlib/cheatsheets)
- [SciPy Matplotlib Reference](https://docs.scipy.org/doc/matplotlib/)
- [DataCamp Matplotlib Courses](https://www.datacamp.com/courses/introduction-to-matplotlib)
- [Conda Environment Management](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

---

**Happy learning! 🎓**
