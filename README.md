# Student-Marks-Average-Calculator
This Python script defines a Student class capable of storing a student's name and their marks. It includes a method to calculate the average score from the provided marks.

## Features
* Store student name and their marks.
* Calculate the average score of the marks.

## Usage
To use this program, create an instance of the Student class by passing the student's name and their marks as a list. Then, call the 'calc_avg' method to calculate the average score.

## Example

    s1 = Student("Nibedita", [97, 98, 95])
    print(f"{s1.name}'s marks = {s1.marks}")
    avg = s1.calc_avg()
    print(f"So, her average score = {avg}")


## Output:
    Nibedita's marks = [97, 98, 95]
    So, her average score = 96.66666666666667


## Requirements
* Python 3.12.1
(I'm using this version, you may be using a different one, but no need to worry about that.)


## Installation
No installation is required. You just need Python 3.12.1 to run this script.


## Contributing
Feel free to fork the repository and submit pull requests.


## License
MIT
