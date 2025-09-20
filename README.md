# 🔌 Electricity Billing System

[![Java](https://img.shields.io/badge/Java-100%25-orange)](https://www.java.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)](https://github.com/code-divyu/Electricity-billing-system)

## 📋 Project Overview

The **Electricity Billing System** is a comprehensive Java-based desktop application designed to streamline and automate electricity bill management. This system provides utilities, customers, and administrators with an efficient platform to manage electricity consumption tracking, billing calculations, customer records, and payment processing.

### 🎯 Key Objectives
- Automate electricity billing processes
- Provide accurate consumption-based billing
- Maintain comprehensive customer records
- Enable efficient bill generation and management
- Offer user-friendly interface for all stakeholders

## ✨ Features

### 🏠 Customer Management
- **Customer Registration**: Easy customer onboarding with detailed profile management
- **Account Management**: Update customer information, connection details, and service preferences
- **Connection Types**: Support for domestic, commercial, and industrial connections

### 📊 Billing & Consumption
- **Smart Meter Reading**: Input and manage electricity consumption data
- **Tiered Pricing**: Calculate bills based on consumption slabs and tariff rates
- **Tax Calculation**: Automatic computation of applicable taxes and surcharges
- **Bill History**: Maintain comprehensive billing history for each customer

### 💳 Payment Processing
- **Multiple Payment Options**: Cash, check, and digital payment tracking
- **Payment History**: Complete payment records with transaction details
- **Due Date Management**: Automated reminders and penalty calculations
- **Receipt Generation**: Professional bill receipts and payment confirmations

### 📈 Reports & Analytics
- **Usage Reports**: Monthly and yearly consumption analysis
- **Revenue Reports**: Financial summaries and collection statistics
- **Customer Analytics**: Usage patterns and customer insights
- **Export Functionality**: Export reports to PDF and Excel formats

### 🔧 Administrative Features
- **User Role Management**: Admin, operator, and customer access levels
- **Tariff Management**: Configure electricity rates and pricing structures
- **System Configuration**: Customize system settings and parameters
- **Database Management**: Backup and restore functionality

## 🛠️ Technologies Used

- **Programming Language**: Java (100% of codebase)
- **GUI Framework**: Java Swing for desktop interface
- **Database**: MySQL/SQLite for data persistence
- **IDE**: NetBeans (project structure included)
- **Build Tool**: Ant (build.xml included)
- **Documentation**: Markdown for README and documentation

## 🚀 Getting Started

### 📋 Prerequisites

Before running the application, ensure you have the following installed:

- **Java Development Kit (JDK) 8 or higher**
  ```bash
  java -version  # Should show version 1.8 or higher
  ```
- **IDE (recommended)**:
  - NetBeans IDE 12 or higher
  - IntelliJ IDEA
  - Eclipse IDE
- **Database** (optional for advanced features):
  - MySQL 5.7 or higher
  - SQLite (embedded option)

### 📥 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/code-divyu/Electricity-billing-system.git
   cd Electricity-billing-system
   ```

2. **Open in IDE**
   - **NetBeans**: File → Open Project → Select the cloned directory
   - **IntelliJ IDEA**: File → Open → Select the project directory
   - **Eclipse**: File → Import → Existing Projects into Workspace

3. **Build the Project**
   ```bash
   # Using Ant (if ant is installed)
   ant compile
   
   # Or build through your IDE's build system
   ```

4. **Database Setup** (if using MySQL)
   ```sql
   CREATE DATABASE electricity_billing;
   -- Import provided SQL schema if available
   ```

### ▶️ Running the Application

1. **Through IDE**:
   - Locate the main class file in `/src` directory
   - Right-click on main class → Run File

2. **Command Line**:
   ```bash
   # Navigate to project directory
   cd Electricity-billing-system
   
   # Compile (if not already compiled)
   javac -cp "src" src/main/MainClass.java
   
   # Run the application
   java -cp "src" main.MainClass
   ```

## 📖 Usage Guide

### 🔐 System Login
1. Launch the application
2. Enter admin credentials (default: admin/admin)
3. Access the main dashboard

### 👤 Managing Customers
1. **Add New Customer**:
   - Navigate to Customer → Add New Customer
   - Fill in customer details (name, address, connection type)
   - Generate unique customer ID
   - Save customer profile

2. **Update Customer Information**:
   - Search customer by ID or name
   - Modify required fields
   - Save changes

### 📊 Billing Process
1. **Record Meter Reading**:
   - Select customer account
   - Input current meter reading
   - System calculates consumption automatically

2. **Generate Bill**:
   - Review consumption and rates
   - Apply applicable taxes and charges
   - Generate and print bill

3. **Process Payment**:
   - Record payment against bill
   - Update customer account
   - Generate payment receipt

### 📈 Generate Reports
1. Select report type (usage, revenue, customer)
2. Choose date range and filters
3. Export or print report

## 🏗️ Project Structure

```
Electricity-billing-system/
├── build/                  # Compiled classes
│   └── classes/           # Java bytecode files
├── nbproject/             # NetBeans project files
│   ├── build-impl.xml     # Build configuration
│   └── project.properties # Project settings
├── src/                   # Source code
│   ├── main/              # Main application classes
│   ├── models/            # Data models
│   ├── views/             # GUI components
│   └── utils/             # Utility classes
├── build.xml              # Ant build script
├── manifest.mf            # JAR manifest file
└── README.md              # Project documentation
```

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 🔄 How to Contribute

1. **Fork the Repository**
   ```bash
   # Click the 'Fork' button on GitHub or
   gh repo fork code-divyu/Electricity-billing-system
   ```

2. **Create Feature Branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make Changes**
   - Follow Java coding standards
   - Add comments and documentation
   - Test your changes thoroughly

4. **Commit Changes**
   ```bash
   git add .
   git commit -m "Add amazing feature: detailed description"
   ```

5. **Push to Branch**
   ```bash
   git push origin feature/amazing-feature
   ```

6. **Open Pull Request**
   - Provide clear description of changes
   - Include screenshots if UI changes are made
   - Reference any related issues

### 📝 Contribution Guidelines

- Follow existing code style and conventions
- Write clear, concise commit messages
- Include documentation for new features
- Add unit tests for new functionality
- Ensure backward compatibility
- Update README if needed

### 🐛 Reporting Issues

Found a bug? Please help us improve:

1. Check existing issues to avoid duplicates
2. Create detailed issue report with:
   - Steps to reproduce
   - Expected vs actual behavior
   - System environment details
   - Screenshots if applicable

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### 📋 MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

## 👨‍💻 Author

**Divyu** - [@code-divyu](https://github.com/code-divyu)

- 💼 LinkedIn: [Connect with me](https://linkedin.com/in/code-divyu)
- 📧 Email: [Get in touch](mailto:contact@codedivyu.dev)
- 🐦 Twitter: [@code_divyu](https://twitter.com/code_divyu)

## 🙏 Acknowledgments

- Thanks to the Java community for excellent documentation
- Inspired by real-world electricity billing systems
- Special thanks to contributors and testers
- NetBeans IDE for excellent Java development support

## 📞 Support

Need help? Here are your options:

- 📖 **Documentation**: Check this README and code comments
- 🐛 **Issues**: [Create an issue](https://github.com/code-divyu/Electricity-billing-system/issues)
- 💬 **Discussions**: [Join discussions](https://github.com/code-divyu/Electricity-billing-system/discussions)
- 📧 **Direct Contact**: Reach out via email for urgent matters

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

*Built with ❤️ by [Divyu](https://github.com/code-divyu)*

</div>
