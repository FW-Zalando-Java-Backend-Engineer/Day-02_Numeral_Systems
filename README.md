### **📘 Day-02: Understanding & Converting Numeral Systems**  
Welcome to **Day-02** of our Java learning journey! Today, we took a deep dive into **numeral systems**, focusing on converting numbers between different bases and implementing these conversions in Java.

---

## **📌 Lesson Overview**  
### **1️⃣ Introduction to Java (Recap)**  
- Running our first Java program: `"Hello, World!"`  
- Understanding **classes, methods, variables**, and the **main method**.  

### **2️⃣ Converting Decimal to Other Bases**  
We explored different methods to convert **decimal numbers** (Base-10) into other number systems.  

#### **🔹 Decimal to Binary (Base-10 → Base-2)**  
- Using **Repeated Division by 2**:  
  1. Divide the number by 2.  
  2. Record the remainder (0 or 1).  
  3. Repeat until the quotient is 0.  
  4. Read the remainders in **reverse order**.  

  ✅ **Example:** Convert **25** (Base-10) to **Binary** → **11001₂**  

#### **🔹 Decimal to Octal (Base-10 → Base-8)**  
- Using **Repeated Division by 8**:  
  ✅ **Example:** Convert **125** (Base-10) to **Octal** → **175₈**  

#### **🔹 Decimal to Hexadecimal (Base-10 → Base-16)**  
- Using **Repeated Division by 16**:  
  ✅ **Example:** Convert **254** (Base-10) to **Hexadecimal** → **FE₁₆**  

---

### **3️⃣ Converting Binary to Other Bases**  
We also learned how to convert **binary numbers** (Base-2) into other numeral systems.  

#### **🔹 Binary to Decimal (Base-2 → Base-10)**  
- Using the **Positional Value Method**:  
  - Multiply each binary digit by **2^position** and sum them up.  
  ✅ **Example:** Convert **1011₂** to **Decimal** → **11₁₀**  

#### **🔹 Binary to Octal (Base-2 → Base-8)**  
- Group binary digits into sets of **three** (from right to left).  
  ✅ **Example:** Convert **101110₂** to **Octal** → **56₈**  

#### **🔹 Binary to Hexadecimal (Base-2 → Base-16)**  
- Group binary digits into sets of **four**.  
  ✅ **Example:** Convert **110110101010₂** to **Hexadecimal** → **DAA₁₆**  

---

## **📜 Code Examples**  
### **🖥️ Running Our First Java Program**  
```java
public class Main {  
    public static void main(String[] args) {  
        System.out.println("Hello, World!");  // Printing output  

        int decimal = 25;  
        int binary = 0b11001; // Binary (Base 2)  
        int octal = 031; // Octal (Base 8)  
        int hexadecimal = 0x19; // Hexadecimal (Base 16)  

        System.out.println("Decimal: " + decimal);  
        System.out.println("Binary: " + binary);  
        System.out.println("Octal: " + octal);  
        System.out.println("Hexadecimal: " + hexadecimal);  
    }  
}
```

### **🖥️ Decimal to Binary Conversion in Java**  
```java
public class DecimalToBinary {  
    public static void main(String[] args) {  
        int decimalNumber = 42;  
        String binaryNumber = Integer.toBinaryString(decimalNumber);  
        System.out.println("Binary of " + decimalNumber + " is " + binaryNumber);  
    }  
}
```

### **🖥️ Binary to Decimal Conversion in Java**  
```java
public class BinaryToDecimal {  
    public static void main(String[] args) {  
        String binaryCode = "101010";  
        int decimalCode = Integer.parseInt(binaryCode, 2);  
        System.out.println("Decimal of " + binaryCode + " is " + decimalCode);  
    }  
}
```

---

## **🎯 Hands-on Exercises**  
✅ Convert **255** to **Binary, Octal, and Hexadecimal**.  
✅ Convert **1101 (Binary)** to **Decimal**.  
✅ Modify the **Decimal to Binary Converter** to support **Octal & Hexadecimal conversions**.  

📌 **Additional Assignments:**  
- [Number System Conversions](https://classroom.github.com/a/SfYN17PV)  
- [50 Practice Questions - Number System Conversions](https://classroom.github.com/a/4Z7uitFx)  

---

## **✅ Summary**  
🔹 Java programs start from the **main method**.  
🔹 **Numeral systems** (Binary, Octal, Hexadecimal) are essential in computing.  
🔹 We implemented **Decimal to Binary, Octal, and Hexadecimal conversions** using Java.  
🔹 We performed **Binary to Decimal, Octal, and Hexadecimal conversions**.  

---

## **📚 Additional Resources**  
- [Java Documentation](https://docs.oracle.com/en/java/)  
- [Binary Number System](https://en.wikipedia.org/wiki/Binary_number)  
- [Hexadecimal System](https://en.wikipedia.org/wiki/Hexadecimal)  
- **Video Lesson Recording:** *[Link to be added]*  
- **Reference Video Watched:** [Understanding Number Systems](https://www.youtube.com/watch?v=FFDMzbrEXaE)
- **Class Document:**[Numeral System Conversion](https://docs.zoom.us/doc/ExIH5yCZSGKzReOenMwE-g)

🚀 **Great job today! Keep practicing, and see you on Day-03!** 💡🎉  
