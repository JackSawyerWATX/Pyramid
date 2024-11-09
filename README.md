# Pyramid Generator

This project generates a pyramid shape using a specified character (`!` by default) and creates either a standard or 
inverted pyramid based on the `inverted` flag. The pyramid's height is defined by the `count` variable.

## Features:
- **Customizable character**: You can change the character used to form the pyramid.
- **Customizable size**: The height of the pyramid is controlled by the `count` variable.
- **Inverted option**: The `inverted` flag allows the pyramid to be built either in the standard or inverted form.
  
## How it works:
1. The `padRow` function generates each row with appropriate padding and characters.
2. A loop adds the rows to either the beginning or end of the `rows` array based on the value of `inverted`.
3. The rows are then joined into a final string, which is logged to the console.

## How to Use:

    Set the count to your desired pyramid height.
    Optionally, set the inverted variable to true to create an inverted pyramid.
    Modify the character if you want a different symbol for the pyramid.

## License:

This project is licensed under the MIT License - see the LICENSE file for details.
