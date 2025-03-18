### **📘 Day-02: Introduction to Numeral Systems**
Welcome to **Day-02** of our Java learning journey! Today, we explore **numeral systems** and learn how to handle them in Java.

---

## **📌 Lesson Overview**
### **1️⃣ Understanding Java Basics**
- What is Java?
- Introduction to **Classes, Methods, Variables, and the Main Method**
- Writing our **first Java program**: `HelloWorld.java`

### **2️⃣ Understanding Numeral Systems**
- Decimal (Base-10)
- Binary (Base-2)
- Octal (Base-8)
- Hexadecimal (Base-16)
- Why are these numeral systems important in computing?

### **3️⃣ Working with Numeral Systems in Java**
- Printing numbers in **different bases**.
- Converting **decimal to binary, octal, and hexadecimal**.
- Converting **binary to decimal**.

### **4️⃣ Binary Arithmetic in Java**
- Binary **addition**, **subtraction**, and **multiplication** using Java.

### **5️⃣ Live Coding Exercise**
- Build a **Decimal to Binary Converter** using `Scanner` in Java.

### **6️⃣ Final Project (Optional)**
- Create a **Number System Converter** that supports **all conversions**.

---

## **📜 Code Examples**
### **🖥️ Printing Numbers in Different Bases**
```java
public class NumeralSystems {
    public static void main(String[] args) {
        int decimal = 42;
        int binary = 0b101010; // Binary (Base 2)
        int octal = 052; // Octal (Base 8)
        int hexadecimal = 0x2A; // Hexadecimal (Base 16)

        System.out.println("Decimal: " + decimal);
        System.out.println("Binary: " + Integer.toBinaryString(decimal));
        System.out.println("Octal: " + Integer.toOctalString(decimal));
        System.out.println("Hexadecimal: " + Integer.toHexString(decimal));
    }
}
```

### **🖥️ Decimal to Binary Conversion**
```java
public class DecimalToBinary {
    public static void main(String[] args) {
        int decimal = 100;
        String binary = Integer.toBinaryString(decimal);
        System.out.println("Binary of " + decimal + " is: " + binary);
    }
}
```

### **🖥️ Binary Addition**
```java
public class BinaryAddition {
    public static void main(String[] args) {
        int num1 = 0b1011; // 11 in decimal
        int num2 = 0b1101; // 13 in decimal
        int sum = num1 + num2;
        System.out.println("Sum in Binary: " + Integer.toBinaryString(sum));
        System.out.println("Sum in Decimal: " + sum);
    }
}
```

### **🖥️ Live Coding: Decimal to Binary Converter**
```java
import java.util.Scanner;

public class DecimalToBinaryConverter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a decimal number: ");
        int decimal = scanner.nextInt();
        String binary = Integer.toBinaryString(decimal);
        System.out.println("Binary representation: " + binary);
    }
}
```

---

## **🎯 Hands-on Exercises**
🔹 Convert **255** to Binary, Octal, and Hexadecimal.  
🔹 Convert **1101 (Binary)** to Decimal.  
🔹 Modify the **Decimal to Binary Converter** to support **Octal & Hexadecimal** conversions.

---

## **✅ Summary**
🔹 Java programs start from the **main method**.  
🔹 Numeral systems like **Binary, Octal, Hexadecimal** are essential in computing.  
🔹 Java provides methods like `toBinaryString()`, `toOctalString()`, and `toHexString()`.  
🔹 We performed **Binary Arithmetic** in Java.  
🔹 We built a **Decimal to Binary Converter**.

---

## **📚 Additional Resources**
- [Java Documentation](https://docs.oracle.com/en/java/)
- [Binary Number System](https://en.wikipedia.org/wiki/Binary_number)
- [Hexadecimal System](https://en.wikipedia.org/wiki/Hexadecimal)

---

🚀 **Great job today! Keep practicing and get ready for Day-03!** 💡🎉

---
