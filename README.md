# ContaTerminal

This is a simple Java console application that simulates the creation of a bank account. The user is prompted to enter their account number, agency number, client name, and initial balance. After the details are provided, a summary message is displayed.

## Project Structure

The project follows the typical Java project structure with source files located in the `src` directory and compiled classes output to the `bin` directory. External libraries, if any, should be placed in the `lib` directory.

├── src
│ └── ContaTerminal.java
├── bin
├── lib
└── README.md


## Prerequisites

- Java Development Kit (JDK) installed.
- An IDE or text editor (e.g., Visual Studio Code).

## Getting Started

1. **Clone the repository** (if applicable):
   ```sh
   git clone <repository-url>

2 - Open the project:

 - Open Visual Studio Code.
 - Open the project folder.
   
3 - Build the project:

 -  Make sure your tasks.json in the .vscode folder has the following configuration:


    ```
    {
        "version": "2.0.0",
        "tasks": [
            {
                "type": "java (build)",
                "paths": [
                    "${workspace}"
                ],
                "isFullBuild": true,
                "group": {
                    "kind": "build",
                    "isDefault": true
                },
                "problemMatcher": [],
                "label": "java (build): Build Workspace",
                "detail": "$(tools) Build all the Java projects in workspace."
            }
        ]
    }
    
4 - Run the application:

 - Open the terminal in Visual Studio Code.
 - Navigate to the src directory.
 - Compile the ContaTerminal.java file:

       javac -d ../bin ContaTerminal.java
 
 - Run the compiled class:

       java -cp ../bin ContaTerminal

##Usage

1 - When prompted, enter the following details:

 - Account number
 - Agency number
 - Client name
 - Initial balance

2 - The application will display a summary message with the provided details.

Example

    Por favor, digite o número da Agência:
    1234
    Por favor, digite a Agência:
    5678
    Por favor, digite o nome do cliente:
    John Doe
    Por favor, digite o saldo do cliente:
    1000.50
    Olá John Doe, obrigado por criar uma conta em nosso banco, sua agência é 5678, conta 1234 e seu saldo 1000.50 já está disponível para saque.

Author
MarcuusCorrea

