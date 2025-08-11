# Python List Operations Project

## Description
This project demonstrates basic list operations in Python, including creating a list, appending elements, inserting values, extending the list, removing elements, sorting, and finding the index of a specific value. The code is simple and serves as an educational example for beginners learning Python list manipulation.

## Features
- Create an empty list
- Append multiple elements
- Insert a value at a specific position
- Extend the list with another list
- Remove the last element
- Sort the list in ascending order
- Find the index of a specific value

## Requirements
- Python 3.x

## Installation
1. Ensure Python 3.x is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
2. Clone or download this repository to your local machine.
3. No additional dependencies are required.

## Usage
1. Save the following code in a file named `list_operations.py`:

```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend my_list with another list
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort the list in ascending order
my_list.sort()

# Find and print the index of 30
print(my_list.index(30))

# Print the final list to see the result
print(my_list)
```

2. Open a terminal or command prompt.
3. Navigate to the directory containing `list_operations.py`.
4. Run the script using:
   ```bash
   python list_operations.py
   ```

## Output
When you run the script, it will output:
```
3
[10, 15, 20, 30, 40, 50, 60]
```
- `3` is the index of the value `30` in the sorted list.
- The second line shows the final sorted list.

## Contributing
Contributions are welcome! If you’d like to enhance this project (e.g., add more list operations or improve documentation), please:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License
This project is licensed under the MIT License.
