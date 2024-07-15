```python
import string
import random

def generate_password(length):
# Define the characters to be used in the password
    characters = string.ascii_letters + string.digits + string.punctuation
# Generate the password
    password = ''.join(random.choice(characters) for _ in range(length))
    return password

def main():
# Prompt the user to specify the desired length of the password
    length = int(input("Enter the desired length of the password: "))
# Generate the password
    password = generate_password(length)
# Display the password
    print("Generated Password: ", password)

if __name__ == "__main__":
    main()

```

    Enter the desired length of the password: 7
    Generated Password:  Z6lgA}N
    


```python

```
