# 📚 Java Streams Project

### 🚀 Project Overview
This project is focused on demonstrating how Java Streams work, which are a key feature introduced in Java 8 that allow functional-style operations on collections of elements.

Streams enable you to perform operations like filtering, mapping, reducing, and more in a declarative and concise way.

### 📑 Table of Contents
* Features
* Technologies
* Installation
* Usage
* Examples
* License


### ✨ Features
Declarative Operations: Process data collections like Lists, Sets, or Arrays.
Functional Programming: Leverage lambda expressions for clean and efficient code.
Built-in Operations: Perform common tasks like filtering, mapping, and reducing with ease.
Parallel Streams: Process large collections more efficiently with parallel processing.

### 🛠️ Technologies
Java 8+ - Streams API requires Java 8 or higher.
Maven - For dependency management.


### 📥 Installation
Clone the repository:

### bash
Copy code
git clone https://github.com/Leticia12git/streams-java.git
Navigate into the project directory:

### bash
Copy code
cd java-streams-project
Build the project using Maven:

bash
Copy code
mvn clean install

### ▶️ Usage
You can run the project to see different examples of how Java Streams can be used. Here are some of the most common operations demonstrated:

Filtering
java
Copy code
List<String> names = Arrays.asList("John", "Jane", "Jack");
List<String> filteredNames = names.stream()
.filter(name -> name.startsWith("J"))
.collect(Collectors.toList());
Mapping
java
Copy code
List<Integer> numbers = Arrays.asList(1, 2, 3);
List<Integer> squares = numbers.stream()
.map(number -> number * number)
.collect(Collectors.toList());
Reducing
java
Copy code
List<Integer> numbers = Arrays.asList(1, 2, 3);
int sum = numbers.stream()
.reduce(0, Integer::sum);

💡 Examples
Here are some more examples of operations you can perform with Java Streams:

Filtering a list of integers to keep only even numbers.
Finding the maximum value in a collection.
Counting elements that match a specific condition.
java
Copy code
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);
long count = numbers.stream()
.filter(n -> n % 2 == 0)
.count();


### 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

### 🌟 Contributions
Feel free to contribute to this project by submitting issues or pull requests. Your input is highly appreciated!

### 📧 Contact
GitHub: https://github.com/Leticia12git
Email: leticia.l.silva@outlook.com