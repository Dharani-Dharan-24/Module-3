# (E) Tuple in Python: Check Element Existence

## 🎯 Aim:
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm:
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program:

    tup = eval(input("Enter a tuple of elements with characters and numbers:"))
    if 'n' in tup and 8 in tup :
        print ("The character 'n' and the number (8) are exists in the given tuple")
    elif 'n' in tup and 8 not in tup :
        print ("The character 'n' exists in the given tuple but the number (8) doesn't exist")
    elif 'n' not in tup and 8 in tup :
        print ("The number (8) exists in the given tuple but the character 'n' doesn't exist")
    else:
         print("Both 'n' and 8 are not exist in the givn tuple")

## Output:

<img width="1918" height="519" alt="Screenshot 2025-10-21 095333" src="https://github.com/user-attachments/assets/bee11baa-7909-4950-80b1-ffb930047403" />
<img width="1917" height="112" alt="Screenshot 2025-10-21 100118" src="https://github.com/user-attachments/assets/27ddf1ef-d112-44f4-b647-c6f91e72cc90" />
<img width="1914" height="96" alt="Screenshot 2025-10-21 100222" src="https://github.com/user-attachments/assets/48e956f1-f66c-4535-89c0-2e5334e385db" />
<img width="1917" height="102" alt="Screenshot 2025-10-21 100302" src="https://github.com/user-attachments/assets/03b1ea74-3c81-4722-b3f4-0bb857a5d6c8" />



## Result:

Thus, The Python program that checks if the element `'n'` and the element `8` exist within a given tuple was executed successfully.
