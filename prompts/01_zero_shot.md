# Zero-shot Prompt Template

## Template
You are an expert <ROLE>. Your task is to <TASK>.

Context:
<PASTE_CONTEXT_HERE>

Constraints:
- Output format: <FORMAT>
- Tone: <TONE>
- Must include: <MUST_INCLUDE>
- Must avoid: <MUST_AVOID>

Before answering, verify you understood the task in 1 line.
Then provide the final output.

## Example
You are an expert QA Automation Engineer. Your task is to write test cases.

Context:
We have a login API: POST /login with JSON {email, password}.

Constraints:
- Output format: Markdown table with columns: Test Case, Steps, Expected Result
- Tone: professional
- Must include: positive, negative, security cases
- Must avoid: vague steps
