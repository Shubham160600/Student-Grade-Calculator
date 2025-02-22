# Student Grade Calculator

A simple web-based application designed to calculate student grades based on input marks.

## Overview

This calculator allows users to input four numerical grades, calculates the total score and percentage, assigns a letter grade (A-F), and determines whether the student passes or fails. The interface features a dark green background with white text for better readability.

## Output:

![1](https://github.com/user-attachments/assets/8ba40088-bb9c-4fe3-b341-9678568d4a10)
![2](https://github.com/user-attachments/assets/64c85001-5624-4290-bafe-936104b0203a)

## Features

- **Input Fields:** Four fields for entering numerical marks.
- **Calculation:** Calculates total score and percentage out of 400.
- **Grade Assignment:** Assigns A-F grade based on percentage thresholds.
  - A: ≥90%
  - B: ≥80%
  - C: ≥70%
  - D: ≥60%
  - F: Below 60%
- **Pass/Fail Status:** Pass if ≥60%, Fail otherwise.
- **Simple UI:** Dark green background with white text for clarity.

## Technologies Used

- **HTML5** for structuring content
- **CSS3** for basic styling (colors)
- **JavaScript** for calculations and dynamic updates

## Usage Instructions

1. Open `index.html` in your preferred web browser.
2. Enter four numerical marks in the provided input fields.
3. Click the "Show Percentage" button to calculate results.
4. Results will be displayed below the button:
   - Total Score
   - Percentage
   - Letter Grade (A-F)
   - Pass/Fail Status

## Known Limitations & Future Enhancements

### Known Limitations:
1. Assumes each mark has a maximum value of 100 without validation checks.
2. Basic styling; lacks advanced design elements.

### Future Enhancements:
1. Implement input validation to ensure only numbers are entered within valid ranges (0–100).
2. Improve UI design with more visually appealing elements or responsive layout adjustments.
3. Add error handling mechanisms to handle invalid inputs gracefully.

## License

MIT Open Source License

## Author

Shubham Saurabh
