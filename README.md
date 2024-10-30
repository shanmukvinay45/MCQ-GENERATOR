#  MCQ Generator with Quiz Complexity Evaluator

This project leverages LangChain and OpenAI's GPT-3.5 to automatically generate multiple-choice questions (MCQs) from given text, evaluate their complexity, and fine-tune them to match the cognitive level of the target audience. The tool reads biology content from a PDF or text file, generates MCQs, evaluates the quiz difficulty, and outputs a refined quiz with expert adjustments to enhance learning engagement.

## Features

1. **MCQ Generation**: Generates a specified number of multiple-choice questions from a provided text input.
2. **Quiz Complexity Evaluation**: Assesses the complexity of each question and adjusts tone or wording as needed.
3. **Customizable Quiz Parameters**: Set the subject, number of questions, and tone.
4. **Response JSON Format**: Output is formatted as JSON with questions, choices, and correct answers.
5. **Token Usage Tracking**: Uses LangChain's callback tracking for efficient API token utilization.

## Setup

### Prerequisites
- **Python 3.7+**
- **LangChain** and **OpenAI** packages
- Environment variables stored in a `.env` file, including the OpenAI API key.
