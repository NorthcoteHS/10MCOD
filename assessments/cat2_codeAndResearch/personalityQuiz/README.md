# personalityQuiz

This is one of the available options for your CAT 2 Coding component.

## Description

You will create a personality type quiz that puts the user into a category based on their answers to questions.

Examples:
- Which emoji are you?
- Which Hogwarts house do you belong in?
- A magazine style quiz (eg. "If you answered mostly As, you are easygoing and roll with the punches. Sometimes, you secretly wish you could get your way.")

Be creative with the types of questions you use, and use a calculation or comparison of some sort to assign the final result (it shouldn't be random).

The quiz should ask the series or questions, then output a final result based on the answers.

## Assessment

Your program must use:

- at least one function
- at least one list
- at least one for loop
    - **Note:** Certain "Extension" options may remove the need of a for loop.

Your program will be assessed against [this rubric](../codingRubric.pdf). Note that some extension options (for "Above Level") are listed at the bottom of this page.

## Getting Started

Here's a basic structure ("algorithm") to get you started on your program:

1. Create a list of all your questions.
2. Create a variable to count the number of each answer (or add the score or perform another calculation).
3. Use a for loop to go through each question in your list.
4. Within the for loop, call a function with the question and answer as inputs.
    - The function will ask the question and return an indicator of which option was chosen (such as a number, 0 for a, 1 for b, 2 for c etc.)
    - Note: it may be simplest to add the indicators up and use a range to determine the result.
5. Compute and display the user's result when the for loop has finished.

## Extension

To further improve your project, you may want to:

- ask questions in a random order
- present multiple-choice answers in a random order
- weight questions/answers based on how strongly they affect the user's final personality outcome
- show images with results
    - **Note:** this requires using the [Pillow module](https://pillow.readthedocs.io/en/3.1.x/installation.html#basic-installation) and [this method](https://stackoverflow.com/a/5333261/4080966) or similar