This README provides detailed instructions and explanations for three distinct tasks:
1.	UI Challenge: Interactive Photo Gallery (contained in ui-challenge folder).
2.	Coding Challenge: Array Manipulation and String Transformation (contained in challenges folder)

 .UI Challenge: Interactive Photo Gallery
 
1.	Assets: The assets folder contain all images used in my implementation. 
2.	HTML Structure: The HTML file defines the structure of the gallery, including containers for thumbnails and full-size images. (Located in index file)
3.	CSS Styling: CSS is used to style the gallery and ensure it is responsive. Techniques like Grid or Flexbox are employed to create a layout that adapts to different screen sizes.         (located in css folder).
4.	JavaScript Functionality: JavaScript handles the interactivity:
a.	Clicking on a thumbnail updates the display to show the corresponding full-size image.
b.	Additional interactions and animations are implemented as specified in the Figma designs. (located in js folder)

Coding Challenge 

1: Array Manipulation:
How It Works
1.	Initialization: Two pointers (start and end) are used to represent the current subarray, and a variable (currentSum) keeps track of the sum of the elements within the window defined by these pointers.
2.	Expanding the Window: The end pointer iterates through the array, adding each element to currentSum.
3.	Contracting the Window: If currentSum exceeds the target, the start pointer is moved to the right, and the value at start is subtracted from currentSum. This process continues until currentSum is less than or equal to the target.
4.	Checking for Target: If currentSum equals the target at any point, the function returns true. If the loop completes without finding such a subarray, the function returns false.

2: String Transformation:
Problem Statement
Transform a string based on the following rules:
1.	If the length of the string is divisible by 3, reverse the entire string.
2.	If the length of the string is divisible by 5, replace each character with its ASCII code.
3.	If the length of the string is divisible by both 3 and 5 (i.e., divisible by 15), perform both operations in the specified order.
How It Works
1.	Divisibility Checks: The length of the string is checked for divisibility by 15, 3, and 5 in that order.
2.	Transformation:
o	If the length is divisible by 15, both reversing and ASCII transformation are applied.
o	If divisible by 3 (but not 15), the string is reversed.
o	If divisible by 5 (but not 15), each character is replaced with its ASCII code.
o	If none of these conditions are met, the string remains unchanged.
