# 📐 Vector Operations using NumPy and Matplotlib

This project covers the fundamentals of vector operations using Python. It demonstrates how to create, scale, add, subtract, and perform dot and cross products on vectors using NumPy. Matplotlib is used to visualize vector operations in 2D and 3D.

## 📊 What This Project Does

- Creates 2D and 3D vectors using NumPy.
- Performs vector scaling, addition, and subtraction.
- Calculates dot product and vector projection.
- Calculates cross product and its magnitude.
- Visualizes vector operations using Matplotlib.
- Demonstrates vector addition and subtraction using the tip-to-tail method.

## 🔄 Vector Operations Workflow

Create Vectors  
      ⬇ 
Vector Scaling  
      ⬇  
Vector Addition and Subtraction  
      ⬇ 
Dot Product and Projection  
      ⬇
Cross Product and Magnitude  
      ⬇
2D and 3D Vector Visualization

## 📊 Vector Operations Covered

| Operation          | Description                                          |
|--------------------|------------------------------------------------------|
| Vector Creation    | Creates vectors using `np.array()`                   |
| Vector Scaling     | Multiplies a vector by a scalar                      |
| Vector Addition    | Adds two vectors                                     |
| Vector Subtraction | Subtracts one vector from another                    |
| Dot Product        | Calculates the scalar product using `np.dot()`       |
| Vector Projection  | Projects one vector onto another                     |
| Cross Product      | Calculates a perpendicular vector using `np.cross()` |
| Magnitude          | Calculates vector length using `np.linalg.norm()`    |

## 🧠 Key Concepts Covered

### 1. Vector Creation
- Creating vectors using NumPy arrays.
- Understanding a vector as an arrow from the origin to a point.

### 2. Vector Scaling
- Multiplying a vector by a scalar.
- Understanding how scaling changes magnitude while preserving direction for a positive scalar.

### 3. Vector Addition and Subtraction
- Adding and subtracting corresponding vector components.
- Understanding the tip-to-tail method of vector addition.

### 4. Dot Product
- Calculating the dot product of two vectors.
- Understanding the relationship between vectors and projection.

### 5. Vector Projection
- Projecting vector `a` onto vector `b`.
- Using the formula:

  `proj_b(a) = (a · b) / (b · b) × b`

### 6. Cross Product
- Calculating the cross product of two 3D vectors.
- Understanding that the resulting vector is perpendicular to both input vectors.

### 7. Vector Magnitude
- Calculating the length or magnitude of a vector using the Euclidean norm.

  `||v|| = √(v1² + v2² + ... + vn²)`

## 🛠️ Tech Stack

- **Python** – Programming language
- **NumPy** – Vector creation and mathematical operations
- **Matplotlib** – 2D and 3D vector visualization

## 📈 Visualizations Performed

| Visualization | Purpose |
|---|---|
| Vector Scaling | Compares original and scaled vectors |
| Vector Addition | Demonstrates tip-to-tail vector addition |
| Vector Subtraction | Visualizes the difference between two vectors |
| Dot Product & Projection | Shows the projection of one vector onto another |
| Cross Product | Displays the perpendicular vector in 3D |

## 💡 Key Learnings

1. Learned how to create and manipulate vectors using NumPy.
2. Understood scalar multiplication and its effect on vector magnitude.
3. Practiced vector addition and subtraction.
4. Learned how to calculate dot and cross products.
5. Understood vector projection with its mathematical formula.
6. Learned to calculate vector magnitude using the Euclidean norm.
7. Visualized vector operations using Matplotlib in 2D and 3D.

## 📁 Project Structure

```text
Vector_Operations/
│
├── Vector_Operations.ipynb
└── README.md
```

## 🚀 Future Improvements

- Explore unit vectors and normalization.
- Understand the angle between two vectors.
- Practice more vector operations in 2D and 3D.
- Apply vector mathematics to machine learning concepts.