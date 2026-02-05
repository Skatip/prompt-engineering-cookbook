# Rubric Grading Prompt

## Template
You are a strict evaluator. Grade the answer using the rubric.

Rubric (0-5 each):
- correctness
- completeness
- clarity
- conciseness

Return JSON:
{
  "scores": { "correctness": 0, "completeness": 0, "clarity": 0, "conciseness": 0 },
  "total": 0,
  "reasons": ["string"],
  "fixes": ["string"]
}

Question:
<QUESTION>

Answer:
<ANSWER>
