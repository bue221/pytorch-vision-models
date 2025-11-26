# PyTorch Course

A comprehensive PyTorch learning repository containing interactive Jupyter notebooks covering fundamental concepts from tensor operations to automatic differentiation.

## 📚 Overview

This repository contains a structured collection of tutorials designed to help you learn PyTorch from the ground up. Each notebook focuses on specific concepts and includes practical examples with explanations.

## 🎯 Learning Path

The course is organized in a progressive manner, starting with basic tensor operations and advancing to more complex topics:

1. **Tensor Crash Course** - Introduction to PyTorch tensors
2. **Tutorial 2** - Tensor operations (addition, multiplication, dot product)
3. **Tutorial 3** - Tensor dimensions and reshaping
4. **Tutorial 4** - Matrix multiplication
5. **Derivates** - Automatic differentiation and gradients

## 📋 Prerequisites

- Python 3.10, 3.11, or 3.12
- pip or uv package manager

## 🚀 Installation

### Using uv (Recommended)

```bash
# Install dependencies
uv sync

# Activate virtual environment
source .venv/bin/activate  # On macOS/Linux
# or
.venv\Scripts\activate  # On Windows
```

### Using pip

```bash
# Create virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate  # On macOS/Linux
# or
.venv\Scripts\activate  # On Windows

# Install dependencies
pip install -e .
```

## 📦 Dependencies

- **torch** (>=2.0.0) - PyTorch deep learning framework
- **numpy** (>=1.24.0,<2.0.0) - Numerical computing
- **jupyter** (>=1.0.0) - Jupyter notebook environment
- **notebook** (>=7.0.0) - Jupyter notebook server
- **ipykernel** (>=6.25.0) - IPython kernel for Jupyter
- **matplotlib** (>=3.10.7) - Plotting and visualization

## 📁 Project Structure

```
pytorch-course/
├── classes/
│   ├── TensorCrashCourse.ipynb    # Introduction to tensors
│   ├── Tutorial2.ipynb             # Tensor operations
│   ├── Tutorial3.ipynb              # Tensor dimensions and reshaping
│   ├── Tutorial4.ipynb              # Matrix multiplication
│   └── Derivates.ipynb              # Automatic differentiation
├── main.py                          # Main entry point
├── pyproject.toml                   # Project configuration
├── uv.lock                          # Dependency lock file
└── README.md                        # This file
```

## 📖 Course Content

### Tensor Crash Course
Introduction to PyTorch tensors, their creation, and basic properties.

### Tutorial 2: Tensor Operations
- Element-wise operations (addition, multiplication)
- Scalar multiplication
- Dot product
- Working with tensor arrays

### Tutorial 3: Tensor Dimensions
- Understanding tensor dimensions
- Creating 1D, 2D, and 3D tensors
- Reshaping tensors with `view()`
- Dimension inspection

### Tutorial 4: Matrix Multiplication
- Matrix creation and reshaping
- Matrix multiplication with `torch.matmul()`
- Using the `@` operator for matrix multiplication

### Derivates: Automatic Differentiation
- Understanding gradients and derivatives
- Using `requires_grad=True` for gradient tracking
- Computing gradients with `backward()`
- Working with multiple variables and partial derivatives

## 🎓 Usage

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Navigate to the `classes/` directory and open the notebooks in order.

3. Run each cell sequentially to follow along with the examples.

4. Experiment with the code by modifying values and observing the results.

## 💡 Key Concepts Covered

- **Tensors**: Fundamental data structure in PyTorch
- **Operations**: Element-wise and matrix operations
- **Dimensions**: Understanding tensor shapes and reshaping
- **Automatic Differentiation**: Computing gradients automatically
- **Gradient Tracking**: Using `requires_grad` for backpropagation

## 🔧 Development

### Running the Main Script

```bash
python main.py
```

### Adding New Tutorials

1. Create a new notebook in the `classes/` directory
2. Follow the naming convention: `TutorialN.ipynb` or descriptive name
3. Include clear markdown explanations and code examples

## 📝 Notes

- All notebooks are designed to be run sequentially for best learning experience
- Each notebook builds upon concepts from previous tutorials
- Experimentation is encouraged - modify the code to deepen understanding

## 🤝 Contributing

This is a learning repository. Feel free to:
- Add more tutorials
- Improve existing examples
- Fix errors or clarify explanations
- Add exercises and challenges

## 📄 License

This project is for educational purposes.

## 🔗 Resources

- [PyTorch Official Documentation](https://pytorch.org/docs/stable/index.html)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- [PyTorch Community](https://discuss.pytorch.org/)

---

**Happy Learning! 🚀**

