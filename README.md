It looks like you've got a solid foundation for your lab report! To make this more "report-ready" and easier to read, I’ve restructured your content into a professional format with clear hierarchies and bullet points.

---

## **Experiment: Exploration of the NumPy Library in Python**

### **Aim**
To study the **NumPy** (Numerical Python) library and perform fundamental operations, including:
* **Array Creation:** Building 1D and 2D structures.
* **Attribute Inspection:** Checking dimensions, shapes, and data types.
* **Built-in Functions:** Utilizing specialized methods for array generation and statistical analysis.

---

### **Theory & Key Functions**
NumPy is the core library for scientific computing in Python, providing support for large, multi-dimensional arrays and matrices.

#### **1. Array Metadata & Attributes**
* `ndim`: Returns the number of axes (dimensions) of the array.
* `shape`: A tuple indicating the size of the array in each dimension (e.g., $(3, 3)$ for a 3x3 matrix).
* `dtype`: Describes the type of data held in the array (e.g., `int64`, `float32`).

#### **2. Creation Functions**
* `np.array()`: Converts Python lists or tuples into NumPy arrays.
* `np.zeros()` / `np.ones()`: Initializes arrays of a specified shape filled with $0$ or $1$.
* `np.arange()`: Creates sequences of numbers with a defined step size.
* `np.linspace()`: Creates a specified number of evenly spaced values between two points.



#### **3. Operations & Analysis**
* **Element-wise Arithmetic:** Enables direct addition, subtraction, and multiplication across arrays of the same shape.
* **Statistical Methods:** * `sum()`: Calculates the total of all elements.
    * `mean()` / `median()`: Determines average and middle values.
    * `max()` / `min()`: Identifies the extreme values in a dataset.

---

### **Conclusion**
In this experiment, we successfully explored the **NumPy** library and its pivotal role in numerical computation. By practicing the creation of 1D and 2D arrays, we gained a practical understanding of:
* How to inspect array metadata using `shape` and `ndim`.
* The efficiency of using **vectorized operations** (arithmetic) over standard Python loops.
* The utility of built-in statistical functions for rapid data analysis.

Overall, the experiment demonstrates that NumPy significantly simplifies mathematical and array-based workflows in Python, making it an essential tool for data science and engineering.

---

