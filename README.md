# AnimalSpeakApp
<img src="https://github.com/user-attachments/assets/bb1affd5-b2c1-4ff9-b9be-4699ef704f8e" width="600" />

## Overview

This project demonstrates the concept of "Programming to the Interface" in C#. The application creates a simple form where users can select different animals (such as a dog or a cat) and interact with them through their `Speak` method. The project highlights the use of inheritance, polymorphism, and interfaces to achieve flexibility and extensibility in object-oriented programming.

### Purpose

The primary goal of this project is to understand the principles of programming to an interface, which is an essential concept in object-oriented programming (OOP). The project includes a basic implementation where animals (Dog, Cat) implement a common `Animal` interface, allowing for flexibility in how the animals' `Speak` methods are invoked.

### Features

- **Animal Interface**: Defines a common contract for all animals to implement the `Speak` method.
- **Polymorphism**: Demonstrates polymorphism by allowing different animal objects (Dog, Cat) to be treated as a general `Animal`.
- **Windows Forms Interface**: A simple Windows Form application that allows users to interact with the animals.
  - A ListBox to display animal objects.
  - A button (`Speak`) to trigger the `Speak` method of the selected animal.

## Getting Started

### Prerequisites

To run this project, you will need the following:

- **Visual Studio** (Community Edition or any version that supports Windows Forms)
- **.NET Framework** (Compatible with your Visual Studio version)
- **C# knowledge** (Optional, but helpful for understanding the code)
