# Web Application - ASP.NET (C#)

## 📌 Overview
This is a simple **ASP.NET Web Forms application** that performs **basic arithmetic operations** (Addition, Subtraction, Multiplication, and Division) using C#.

## 🚀 Features
- Accepts two numeric inputs from the user.
- Performs mathematical operations: **Addition, Subtraction, Multiplication, and Division**.
- Displays the result in a textbox.
- Includes **input validation** to handle incorrect inputs.

## 📂 Project Structure
```
WebApplication1/
│-- WebForm1.aspx
│-- WebForm1.aspx.cs
│-- Web.config
│-- README.md
```

## 🔧 Setup & Installation
### **1️⃣ Prerequisites**
- Install **Visual Studio** (Latest version)
- Install **.NET Framework 4.8 or later**
- IIS (Internet Information Services) must be enabled for local hosting.

### **2️⃣ How to Run**
1. Open the project in **Visual Studio**.
2. Build the project (**Ctrl + Shift + B**).
3. Run the project (**F5** or Click on "Start" button).
4. Open `http://localhost:44341/` in a web browser.

## 🛠 Troubleshooting
### **HTTP Error 403.14 - Forbidden**
- Ensure a **default document** (like `WebForm1.aspx`) exists.
- Enable directory browsing (if needed) using the following command in Command Prompt (Admin Mode):
  ```
  appcmd set config /section:system.webServer/directoryBrowse /enabled:true
  ```
- Restart IIS and run the project again.

### **Input String Was Not in a Correct Format Error**
- The input fields should contain only **numeric values**.
- Ensure there is **no empty field** before submitting.
- Use `int.TryParse()` instead of `int.Parse()` to handle invalid inputs gracefully.

## 🤝 Contributors
- **[Ali Hassan khichi 64]**

## 📜 License
This project is open-source under the **MIT License**.

