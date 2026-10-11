# Computer Architecture - CPU & Hardware Components Documentation
Welcome to my Computer Architecture repository! This documentation covers the core hardware and processor components of a computer system.

---

## Core CPU & Hardware Components
The architecture of a computer processor defines how its internal hardware components interact to fetch, decode, and execute instructions. Below are the **5 core components of a computer architecture**:

### 1. Arithmetic Logic Unit (ALU)
* **Description:** The core processing engine of the CPU responsible for executing all mathematical calculations and logical decisions.
* **Key Responsibilities:**
  * Performs arithmetic operations such as addition, subtraction, multiplication, and division.
  * Executes logical operations like AND, OR, NOT, XOR, and bitwise shifts.
  * Handles comparison operations (greater than, less than, equal to) used in conditional branching.

### 2. Control Unit (CU)
* **Description:** Acts as the "brain" or coordinator of the CPU, directing and managing the flow of data and instructions across the entire system.
* **Key Responsibilities:**
  * Fetches program instructions from main memory into the CPU.
  * Decodes instructions to determine what actions need to be performed.
  * Sends precise timing and control signals to the ALU, registers, and memory to execute operations.

### 3. Register File / Registers
* **Description:** Extremely high-speed, small storage locations located directly inside the CPU for holding data currently being processed.
* **Key Responsibilities:**
  * Stores temporary data, intermediate results, and memory addresses during execution.
  * Includes special-purpose registers such as the Program Counter (PC), Instruction Register (IR), Accumulator, and Stack Pointer.
  * Provides lightning-fast data access compared to main memory (RAM).

### 4. Memory & Cache Hierarchy
* **Description:** A multi-layered storage system designed to store instructions and data temporarily or permanently, bridging the speed gap between the fast CPU and slower RAM.
* **Key Responsibilities:**
  * Manages primary memory (RAM) where active programs and data reside.
  * Utilizes high-speed on-chip cache levels (L1, L2, and L3 cache) to keep frequently used data close to the processor.
  * Optimizes overall system execution speed by minimizing memory latency.

### 5. Input/Output (I/O) Subsystem & System Bus
* **Description:** The communication highway and interface that connects the CPU and memory to external peripheral devices.
* **Key Responsibilities:**
  * Manages system buses—including the Data Bus, Address Bus, and Control Bus—to transfer information across components.
  * Coordinates communication with external devices like keyboards, monitors, printers, and storage drives.
  * Handles hardware interrupts and data transfer requests between the processor and peripherals.
