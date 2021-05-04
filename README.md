Advanced Challenge: Transpose the Following Dataset with Arrays

NOTE: The instructions below pertain to a challenge intended for advanced SAS programmers
      as part of the SAS Analytics Explorer's Program. It is provided in this repository as a
      fruitful exercise for my colleagues, friends, and fellow enthusiasts.

      A potential solution is provided in manualtranspose.txt.

INSTRUCTIONS:
Arrays are normally used to transpose wide/horizontal data into a narrow/vertical structure.
How might they be used to do the reverse, from narrow to wide?
Proc transpose should be avoided in order to complete this challenge as it was conceived.

Dataset: sashelp.fish - This dataset is included with base SAS.
Ignore the Weight and Length1-3 variables. Only the species, height, and width variables are relevant.
The height and width should be transposed for each distinct value of species.
As is typical when transposing into a wide structure, many cells in the resulting table should be empty.
Lastly, the table structure should be WIDE in its final form and sorted ascending by species.
