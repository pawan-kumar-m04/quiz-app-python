# Quiz App (Python)

🎯 A simple console-based quiz game made using Python basics.
# quiz.py

questions = {
    "What is the capital of India?": "Delhi",
    "Which language is used in web development?": "HTML",
    "Who developed Python?": "Guido van Rossum"
}

score = 0
for question, answer in questions.items():
    user_ans = input(question + " ")
    if user_ans.strip().lower() == answer.lower():
        print("✅ Correct!")
        score += 1
    else:
        print(f"❌ Wrong! The correct answer is {answer}.\n")

print(f"Your final score: {score}/{len(questions)}")


## Features
- Multiple choice questions
- Score tracking
- Replay option

## Topics Used
- Lists, Loops, Functions, Conditionals

## How to Run
1. Install Python
2. Run: `python quiz.py`
