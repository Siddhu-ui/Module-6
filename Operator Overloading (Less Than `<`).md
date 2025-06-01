
# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## Name   : Siddharth S
## Reg No : 212224040317

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
      class A:
          def __init__(self, a):
              self.a = a
      
          def __lt__(self, other):
              if self.a < other.a:
                  return "ob1 is less than ob2"
              else:
                  return "ob2 is less than ob1"
      
      ob1 = A(10)
      ob2 = A(20)
      print(ob1 < ob2)  # Should print "ob1 is less than ob2"
      print(ob2 < ob1)  # Should print "ob2 is less than ob1"

## Output
![Screenshot 2025-05-20 052520](https://github.com/user-attachments/assets/5daae670-5abd-499d-b431-0e6085e4d56f)

## Result
 Thus, the program is verified successfully.
