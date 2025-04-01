# **Solving Poisson’s Equation: Traditional vs AI-Driven Approaches**  

## **Overview**  
This repository explores different approaches to solving Poisson’s equation, a fundamental partial differential equation in physics and engineering. The project compares the Finite Difference Method (FDM) with Physics-Informed Neural Networks (PINNs) to analyze accuracy, efficiency, and real-world applicability.  

## **Methods Used**  
- **Finite Difference Method (FDM):** A traditional numerical approach that discretizes the domain and applies iterative updates.  
- **Physics-Informed Neural Networks (PINNs):** A deep learning-based method that incorporates the governing physics into the model, offering a mesh-free solution.  

## **Key Features**  
- Implemented FDM for numerical benchmarking  
- Developed a PINN model using TensorFlow  
- Compared results from both methods using visualization and error analysis  
- Analyzed computational efficiency and accuracy  

## **Results & Insights**  
- PINNs can handle complex domains without meshing but require careful tuning.  
- FDM provides reliable solutions but is sensitive to grid resolution.  
- This study highlights the potential of AI in solving PDEs efficiently.  

## **Installation & Usage**  
Clone the repository:  
```bash
git clone https://github.com/your_username/Poisson-PINNs-vs-FDM.git
cd Poisson-PINNs-vs-FDM
```
Run the notebook:  
Use Google Colab or Jupyter Notebook to execute `Poisson_Equation_Solver.ipynb`.  

## **Future Work**  
- Extending PINNs to handle more complex boundary conditions  
- Comparing with Finite Element Methods (FEM)  
- Exploring applications in heat transfer and fluid flow  
