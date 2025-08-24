# Cpp_Experiment_11_Class_and_Object

## 🎯 Aim
To understand the concept of **Objects and Classes in C++** and calculate the **Volume of a Cuboid** using different approaches:
- Direct initialization  
- User input  
- Member functions  
- Encapsulation (private data + public methods)  

---

## 📝 Objectives
- Learn the use of **class** and **object** in C++.  
- Explore the role of **data members** and **member functions**.  
- Implement cuboid volume calculation using multiple methods:
  - User input inside class method  
  - Direct values assigned in object  
  - Member function for calculation  
  - Encapsulation (private data, public method)  
- Compare approaches and understand the advantages of **encapsulation** and **abstraction**.  

---

## 📖 Theory

### 🔹 Class and Object
- A **class** is a blueprint/template defining structure & behavior of objects.  
- **Data members** (variables) store state, while **member functions** define operations.  
- An **object** is an instance of a class, each having its own copy of data members but sharing member functions.  

💡 Example: In a `Cuboid` class →  
- Data Members: `length, width, height`  
- Member Function: `volume()`  
Each object may have different dimensions, but the same method can calculate its volume.  

### 🔹 Encapsulation
- Wrapping of **data + functions** in a class.  
- Provides **data protection** using access specifiers (`public`, `private`, `protected`).  
- Example: Keeping dimensions private but exposing `volume()` ensures safety.  

### 🔹 Abstraction
- Hides implementation details, shows only essential features.  
- User calls `getVolume()` or `display()`, without worrying about internal logic.  

### 🔹 Reusability & Modularity
- Same member function (like `volume()`) works for multiple objects.  
- Improves **readability**, **maintainability**, and reduces redundancy.  

### 🔹 Data Members vs. Member Functions
- **Data Members**: Store properties (`length, width, height`).  
- **Member Functions**: Operate on these members.  
  - `input()` → Takes dimensions from user.  
  - `volume()` → Calculates cuboid volume.  
  - `display()` → Shows results.  

---

## 📊 Observations from Approaches

- **Public data members (direct use):** Easy but insecure.  
- **Methods for input/calculation:** Interactive & modular.  
- **Encapsulation (private data + public methods):** Best practice; ensures security.  

---

## 🔑 Importance of Classes
- Model real-world entities in software.  
- Allow **multiple objects** with different states but common behaviors.  
- Form base for advanced OOP concepts → **Inheritance, Polymorphism, Abstraction**.  

---

## 🗝️ Key Concepts
- **Encapsulation** → Wrapping data + functions.  
- **Access Specifiers** → Control access (public/private).  
- **Reusability** → Methods reused across objects.  
- **Abstraction** → Hide internal details.  
- **Modularity** → Organized, reusable code.  

---

## 📊 Comparison of Programs

| Program Version                          | Input Method                 | Data Members Access | Volume Calculation | Output Example |
|------------------------------------------|------------------------------|---------------------|-------------------|----------------|
| `User_Input_Volume_using_ClassMethod`    | User enters via method       | Public              | Member function    | Volume displayed after input |
| `Volume_using_Class_Cuboid`              | Values directly assigned     | Public              | Formula in `main()`| Directly displayed |
| `Vol_of_Cuboid_Class_Method`             | Values initialized in object | Public              | Member function    | Returned & displayed |
| `Cuboid_with_Encapsulation`              | Private data, public method  | Private             | Public method      | Securely displayed |

---

## 📂 Program Descriptions

### 1️⃣ User Input Volume using Class Method
- Takes dimensions via member function.  
- Calculates & displays volume.  
- Demonstrates interaction between **user** and **object**.  

### 2️⃣ Volume using Class Cuboid
- Dimensions assigned directly to **public data members**.  
- Volume calculated inside `main()`.  
- Simple but unsafe (data directly modifiable).  

### 3️⃣ Volume of Cuboid (Class Method)
- Dimensions initialized directly.  
- `volume()` member function computes and returns result.  
- Cleaner and more modular design.  

### 4️⃣ Cuboid with Encapsulation
- Dimensions marked **private**.  
- Public `volume()` ensures safe calculation.  
- Demonstrates **encapsulation & abstraction**.  

---

## 🧠 Overall Observations
- Direct public data → Simple but insecure.  
- User input via methods → More interactive.  
- Member function calculation → Modular & reusable.  
- Encapsulation with private data → Best practice (security + abstraction).  

---

## ✅ Conclusion
From this experiment, we learned:
- The **role of classes and objects** in structuring programs.  
- Different approaches affect **security, modularity, and design clarity**.  
- **Encapsulation** is the most reliable method for safe data handling.  

> 🏆 Using classes & objects makes programs more organized, reusable, and professional.
