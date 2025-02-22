# Load Balancing Algorithms in Java

## Overview

This project implements both **Static and Dynamic Load Balancing Algorithms** using **Java and Object-Oriented Programming (OOP)** concepts. The user can select from various load balancing techniques to distribute requests among multiple servers.

## Implemented Algorithms

### Static Load Balancing:

1. **Round Robin** - Requests are assigned sequentially to servers.
2. **Weighted Round Robin** - Servers with higher weight get more requests.
3. **IP Hashing** - Assigns requests based on the hash of an IP address.

### Dynamic Load Balancing:

4. **Least Connection** - Assigns requests to the server with the fewest active connections.
5. **Weighted Least Connection** - Similar to Least Connection but considers server weight.
6. **Least Response Time** - Assigns requests to the server with the lowest response time.

## How to Run the Project

### Prerequisites

- Java Development Kit (JDK) installed
- A command-line terminal

### Compilation & Execution

1. Navigate to the project directory in the terminal:
   ```sh
   cd /path/to/project
   ```
2. Compile the Java file:
   ```sh
   javac LoadBalancingDemo.java
   ```
3. Run the program:
   ```sh
   java LoadBalancingDemo
   ```
4. Follow the on-screen prompts to select a load balancing algorithm and assign requests.

## Example Usage

```
Choose Load Balancing Algorithm:
1. Round Robin
2. Weighted Round Robin
3. IP Hashing
4. Least Connection
5. Weighted Least Connection
6. Least Response Time
Enter your choice: 1
Request assigned to: Server2
```

## Future Enhancements

- Implement more load balancing algorithms.
- Add a GUI for better user interaction.
- Simulate real-world traffic distribution.

## License

This project is open-source and free to use under the MIT License.

---

**Author:** Shakil Kathat

