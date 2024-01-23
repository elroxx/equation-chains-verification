# Equation Verification code snippet

Project from 2022

The goal is simple: Verify equation chain to avoid making easy mistakes caused by lack of thoroughness. It allows to take pictures of equation chains (High school level math) and it points where the equality sign does not hold.

This project is an integration of Mathpix OCR, Wolfram symbolic equation solver and verification coupled with LaTeX Markdown for easier output.

## Features
- Takes image as input with an equation or a math snippet written on it.
- Rotation or quality of handwriting does not matter
- Scientific OCR implemented
- Multiple forms and symbols of division, multiplication, addition, logarithms, exponentation all taken in account.
- Works for equation laid out on multiple line or in a single line. Only the equality symbol being present is important
- Works with symbolic and value based algebra
- Ouputs in LaTeX the equation chain that was read
- If two sides of an equality symbol are indeed equal, the equal will be green in LaTeX equation
- If two sides are NOT equal, equality symbol will be an \neq (not equal) symbol in red
