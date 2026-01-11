# ☕ Java Mastery Quiz

**Test your knowledge on Inheritance, Abstract Classes, Functional Programming, and Advanced JVM concepts.**

---

## 📚 Topics Covered
| Core Topics | Advanced Topics |
| :--- | :--- |
| ✅ Inheritance | 🚀 Generics (PECS) |
| ✅ Abstract Classes | 🚀 Concurrency & Atomicity |
| ✅ Polymorphism | 🚀 JVM Memory (Metaspace) |
| ✅ Streams API & Lambdas | 🚀 Parallel Streams |

---

## 🟢 Part 1: Core Concepts (20 Questions)

### 1. Inheritance Basics
**Q1: Which keyword is used to inherit a class in Java?**
A) implement
B) extends
C) inherits
D) super

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) extends</strong>
</details>

---

**Q2: Can a class in Java extend multiple classes?**
A) Yes, always
B) No, Java does not support multiple class inheritance
C) Yes, but only if they are abstract
D) Yes, using the 'implements' keyword

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) No, Java does not support multiple class inheritance</strong>
<br><em>(Note: Java supports multiple inheritance of Interfaces only.)</em>
</details>

---

**Q3: What is the output of `super()` in a constructor?**
A) It calls the static block of the parent class
B) It creates a new instance of the parent class
C) It calls the constructor of the immediate parent class
D) It calls the finalize method

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: C) It calls the constructor of the immediate parent class</strong>
</details>

---

**Q4: If a parent class method is marked `final`, can the child class override it?**
A) Yes
B) No
C) Only if the child class is abstract
D) Only if the return type is changed

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) No</strong>
</details>

---

**Q5: Which access modifier creates a member accessible only within its own package and subclasses?**
A) public
B) private
C) protected
D) default (package-private)

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: C) protected</strong>
</details>

---

**Q6: What is the root class of all classes in Java?**
A) java.lang.Main
B) java.lang.Object
C) java.lang.String
D) java.util.Root

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) java.lang.Object</strong>
</details>

---

### 2. Abstract Classes
**Q7: Can you instantiate an abstract class using the `new` keyword?**
A) Yes, if it has a constructor
B) No, never
C) Yes, if all methods are implemented
D) Yes, using reflection

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) No, never</strong>
</details>

---

**Q8: If a class contains an abstract method, the class must be declared as...**
A) static
B) final
C) abstract
D) public

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: C) abstract</strong>
</details>

---

**Q9: Can an abstract class have a constructor?**
A) Yes
B) No
C) Only if it is private
D) Only if it takes no arguments

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: A) Yes</strong>
<br><em>(It is used to initialize the state of the abstract class when a subclass is instantiated.)</em>
</details>

---

**Q10: Which statement is TRUE regarding Abstract Classes vs Interfaces (pre-Java 8)?**
A) Interfaces can have state (instance variables)
B) Abstract classes can implement methods
C) A class can extend multiple abstract classes
D) Abstract classes cannot have static methods

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) Abstract classes can implement methods</strong>
</details>

---

**Q11: Can an abstract class implement an interface?**
A) Yes, but it must implement all methods
B) No
C) Yes, and it is not required to implement all interface methods
D) Only if the interface is functional

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: C) Yes, and it is not required to implement all interface methods</strong>
</details>

---

**Q12: Can an abstract method be `private`?**
A) Yes
B) No
C) Yes, but only in static classes
D) Yes, if the class is final

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) No</strong>
<br><em>(Abstract methods are meant to be overridden, and private methods cannot be overridden.)</em>
</details>

---

### 3. Functional Programming
**Q13: Which interface must a lambda expression match?**
A) Any interface
B) Functional Interface
C) Abstract Interface
D) Marker Interface

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) Functional Interface</strong>
</details>

---

**Q14: Which annotation ensures an interface is a Functional Interface?**
A) @Override
B) @FunctionalInterface
C) @Lambda
D) @Interface

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) @FunctionalInterface</strong>
</details>

---

**Q15: What does `stream().map()` do?**
A) Filters elements
B) Transforms each element into another object
C) Sorts the elements
D) Reduces the list to a single value

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) Transforms each element into another object</strong>
</details>

---

**Q16: Which of the following is a built-in Functional Interface in `java.util.function`?**
A) Predicate
B) Action
C) Executor
D) Runner

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: A) Predicate</strong>
</details>

---

**Q17: What is the return type of `stream().filter(...)`?**
A) List
B) Boolean
C) Stream
D) Optional

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: C) Stream</strong>
<br><em>(It is an intermediate operation.)</em>
</details>

---

**Q18: What is the syntax for a Method Reference in Java?**
A) Class->method
B) Class::method
C) Class.method()
D) Class:method

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) Class::method</strong>
</details>

---

**Q19: `Consumer<T>` functional interface has a method named...**
A) get()
B) apply()
C) test()
D) accept()

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: D) accept()</strong>
</details>

---

**Q20: Are Streams in Java reusable (can you call terminal operations twice)?**
A) Yes, always
B) No, a stream closes once a terminal operation is called
C) Yes, if you use .reset()
D) Only parallel streams are reusable

<details>
<summary><strong>⬇️ View Answer</strong></summary>
<br>
<strong>Correct Answer: B) No, a stream closes once a terminal operation is called</strong>
</details>

---
<br>

## 🔴 Part 2: Advanced Mastery (10 Questions)

**Q1: [Generics] Which statement about `List<? extends Number>` is true (PECS rule)?**
A) You can add Integers to it
B) You can add Numbers to it
C) You can only read from it (get Number), but cannot add items (except null)
D) It is exactly the same as List<Number>

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: C</strong>
<br>
<em>Explanation: PECS stands for "Producer Extends, Consumer Super". Since the list could be a List of Integer OR a List of Double, Java cannot guarantee type safety if you try to add anything. You can only "Produce" (read) from it.</em>
</details>

---

**Q2: [Concurrency] What does the `volatile` keyword guarantee?**
A) Atomicity of operations
B) Visibility of changes to variables across threads
C) Mutual exclusion (locking)
D) Prevention of deadlocks

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: B</strong>
<br>
<em>Explanation: Volatile ensures that the value of a variable is always read from/written to main memory (happens-before relationship), ensuring visibility. It does NOT guarantee atomicity (e.g., i++ is not safe).</em>
</details>

---

**Q3: [Interfaces] If two interfaces define the same default method and a class implements both, what happens?**
A) Runtime Error
B) The first interface's method is used
C) Compilation Error (Diamond Problem)
D) The class randomly picks one

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: C</strong>
<br>
<em>Explanation: Java will throw a compilation error to prevent ambiguity. The implementing class MUST override the method to resolve which logic to use (or define its own).</em>
</details>

---

**Q4: [Streams] What is the result of calling `stream.parallel()` on a small list?**
A) Always faster performance
B) Always slower performance
C) It creates a new thread for every element
D) Often slower due to thread management overhead

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: D</strong>
<br>
<em>Explanation: Parallel streams use the Fork/Join framework. For small datasets, the overhead of context switching and thread management often exceeds the time saved by parallel execution.</em>
</details>

---

**Q5: [JVM] Where are static variables stored in Java 8+?**
A) Stack Memory
B) Eden Space
C) Metaspace (or Heap depending on implementation)
D) PermGen

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: C</strong>
<br>
<em>Explanation: PermGen was removed in Java 8. Static variables (which are part of the Class object) are stored in the Heap/Metaspace area.</em>
</details>

---

**Q6: [Exceptions] What happens if a `finally` block throws an exception while the `try` block also threw one?**
A) Both exceptions are thrown
B) The `try` exception is thrown, `finally` is ignored
C) The `finally` exception suppresses the `try` exception
D) JVM crashes

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: C</strong>
<br>
<em>Explanation: The exception thrown in the `finally` block will propagate up the stack, and the original exception from the `try` block is lost (unless you manually use `addSuppressed`).</em>
</details>

---

**Q7: [Functional] What is the difference between `map()` and `flatMap()`?**
A) map() flattens nested lists, flatMap() does not
B) flatMap() transforms each element into a Stream and then flattens the results
C) They are identical
D) flatMap() is only for optional values

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: B</strong>
<br>
<em>Explanation: `map` creates a stream of streams (`Stream<Stream<R>>`) if the function returns a stream. `flatMap` flattens that structure into a single stream (`Stream<R>`).</em>
</details>

---

**Q8: [Collections] Why is `ConcurrentHashMap` faster than `Hashtable`?**
A) It is not synchronized
B) It locks the entire map for every write
C) It uses lock striping (segment locking) allowing concurrent reads/writes
D) It uses native C++ code

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: C</strong>
<br>
<em>Explanation: Hashtable uses a single lock for the entire map (coarse-grained). ConcurrentHashMap locks only specific segments (fine-grained), allowing multiple threads to write to different segments simultaneously.</em>
</details>

---

**Q9: [Reflection] Can Reflection access private fields of a class?**
A) No, private means private
B) Yes, by calling `setAccessible(true)`
C) Only if the class is in the same package
D) Only if the SecurityManager is disabled

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: B</strong>
<br>
<em>Explanation: Reflection is powerful and can bypass standard access control checks using `field.setAccessible(true)`.</em>
</details>

---

**Q10: [Core] Is `String` in Java mutable or immutable?**
A) Mutable
B) Immutable
C) Mutable if created with 'new'
D) Immutable only if interned

<details>
<summary><strong>⬇️ View Answer & Explanation</strong></summary>
<br>
<strong>Correct Answer: B</strong>
<br>
<em>Explanation: Strings are always immutable in Java. This allows for the String Pool, security (passwords), and thread safety without synchronization.</em>
</details>

---
<p align="center">Made with ❤️ for Java Developers</p>
