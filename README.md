# Banking System in Core Java

A traditional Desktop Banking System application developed using Core Java and Java Swing. This project provides a graphical user interface (GUI) to manage banking operations such as creating new accounts, deleting accounts, conducting transactions (deposits and withdrawals), and viewing account details.

## Features

- **New Account Creation**: Register new clients into the banking system with basic details.
- **Account Management**: Update customer details and remove accounts from the system.
- **Transactions**: Perform basic banking operations securely:
  - Deposit Money
  - Withdraw Money
- **Search & View**: 
  - Find accounts by Account Number or Customer Name.
  - View individual customer details or browse through all customer records.
- **Customizable UI Themes**: Toggle through multiple visual themes provided by custom Java classes (`AquaTheme`, `GrayTheme`, `SolidTheme`, etc.).

## Technologies Used

- **Java SE Development Kit**: The core functional programming logic.
- **Java Swing & AWT**: Used for building the Graphical User Interface components.
- **Local File Storage**: Uses `Bank.dat` for persistent storage of account records locally.

## Getting Started

### Prerequisites

Ensure you have **Java Development Kit (JDK)** installed on your machine.
You can verify your installation by running:

```bash
java -version
javac -version
```

### Installation & Running

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pavanganeshpg/Banking-System-in-Core-Java.git
   cd Banking-System-in-Core-Java
   ```

2. **Compile the source files**:
   Due to some special characters in the codebase, be sure to compile the Java files with the specific `ISO-8859-1` encoding:
   ```bash
   javac -encoding ISO-8859-1 *.java
   ```

3. **Run the Application**:
   Start the application by running the main entry point:
   ```bash
   java Splash
   ```
   *(Wait a moment for the initial splash screen to finish loading before the main banking window appears).*

## Storage System

The application uses an object-serialization-based flat database (`Bank.dat`) to store the customer accounts locally. Make sure this file has read/write permissions.

## Author

- Original creation by Muhammad Wasif Javed (2003).
- Maintained and updated in this repository.
