# Sample Quiz Repository

This is a sample quiz repository demonstrating the Quiz Player format.

## Testing Locally

Start a local server from the project root:

```bash
# From the quiz-player directory
python3 -m http.server 8000
```

Then open:
```
http://localhost:8000/?local=sample-question-repo
```

## Structure

```
sample-question-repo/
├── quiz.json              # Quiz manifest
├── questions/             # Question files
│   ├── q1-typeof.json
│   ├── q2-primitives.json
│   ├── q3-hoisting.json
│   └── q4-closures.json
└── assets/               # Images and media (optional)
```

## Questions Included

1. **typeof null** - Single-choice question about JavaScript type quirks
2. **Primitive Types** - Multi-select question (4 correct answers)
3. **Hoisting** - Variable hoisting with code example
4. **Closures** - Closure behavior with code example

Each question includes:
- Markdown-formatted explanations
- Code snippets (backticks in question text)
- Category tags
- Mix of single and multi-select formats
