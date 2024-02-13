# Bin2Dec Application Design Document

## Overview

Bin2Dec is a simple application designed to help users practice and understand binary (base 2) mathematics. It allows users to enter binary strings of up to 8 digits, 0's and 1's, and then displays the equivalent decimal (base 10) value of the entered binary number.

## Features

- User can enter up to 8 binary digits in one input field.
- User must be notified if anything other than a 0 or 1 was entered.
- User views the results in a single output field containing the decimal equivalent of the binary number that was entered.

## Constraints

- Arrays may not be used to contain the binary digits entered by the user.
- Determining the decimal equivalent of a particular binary digit in the sequence must be calculated using a single mathematical function.

## Technical Specifications

### User Interface

- **Input Field:** Allows users to enter up to 8 binary digits.
- **Output Field:** Displays the decimal equivalent of the binary number entered by the user.
- **Notification Area:** Displays error messages if anything other than a 0 or 1 is entered.

### Backend Logic

1. **Input Validation:**

   - Check if the entered string contains only 0s and 1s.
   - Limit the input to a maximum of 8 characters.

2. **Binary to Decimal Conversion:**
   - Use a mathematical function to calculate the decimal equivalent of the binary number.
   - Implement a single function to handle the conversion for all 8 digits.
   - Determine the appropriate mathematical function (e.g., natural logarithm) for efficient conversion.

### Error Handling

- Notify the user if the input contains invalid characters (anything other than 0 or 1).
- Notify the user if the input exceeds 8 characters.

### Implementation Strategy

1. **User Interface Design:**

   - Design a simple and intuitive user interface with input and output fields.
   - Implement error notification for invalid inputs.

2. **Input Validation:**

   - Implement input validation logic to ensure the entered string contains only 0s and 1s.
   - Check the length of the input string to ensure it does not exceed 8 characters.

3. **Binary to Decimal Conversion:**

   - Research and select an appropriate mathematical function for binary to decimal conversion.
   - Implement the conversion logic using the chosen function.
   - Verify the correctness of the conversion algorithm for all possible binary inputs.

4. **Integration:**
   - Integrate the frontend and backend components to enable seamless interaction.
   - Test the application thoroughly to ensure all features work as expected.

## Conclusion

Bin2Dec is a straightforward application designed to help users understand binary mathematics by converting binary numbers to decimal equivalents. By following the specified constraints and user stories, we aim to create a simple yet effective tool for educational purposes.

<!-- This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details. -->
