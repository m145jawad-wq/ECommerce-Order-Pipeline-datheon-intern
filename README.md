# E-Commerce Order Pipeline (C++)

## Project Overview
The E-Commerce Order Pipeline is a C++ based project that demonstrates three important software design patterns: Singleton, Factory Method, and Observer.

The system manages e-commerce orders, supports multiple simulated payment methods, and sends real-time order status notifications to different services.

## Features
- Singleton Database Manager
- Factory Method Design Pattern
- Observer Design Pattern
- Credit Card Payment
- UPI Payment
- PayPal Payment
- Cryptocurrency Payment
- Order Status Management
- Logistics Notifications
- Invoicing Notifications
- Email Notifications
- Runtime Polymorphism
- Input Validation

## Design Patterns Used

### 1. Singleton Pattern
Ensures that only one Database Manager instance is created and shared throughout the application.

### 2. Factory Method Pattern
Creates different payment handlers through a common Payment interface.

### 3. Observer Pattern
Automatically notifies Logistics, Invoicing, and Email services whenever an order status changes.

## Technologies Used
- Programming Language: C++
- OOP Concepts
- Abstract Classes
- Inheritance
- Polymorphism
- Smart Pointers
- Design Patterns

## Project Structure
```text
ECommerceOrderPipeline/
│
├── main.cpp
├── README.md
└── .gitignore
```

## How to Run

### Requirements
- C++ Compiler (GCC / MinGW)
- C++17 or later
- VS Code or Code::Blocks

### Compile
```bash
g++ -std=c++17 main.cpp -o ecommerce
```

### Run
Windows:
```bash
ecommerce.exe
```

Linux:
```bash
./ecommerce
```

## Payment Methods
1. Credit Card
2. UPI
3. PayPal
4. Cryptocurrency

## Expected Workflow
1. User selects a payment method.
2. User enters the
