# Tool-use Prompt Templates

## Planner-Executor
You have tools:
- search_docs(query) -> returns relevant text chunks
- get_answer(context, question) -> returns final response

Steps:
1) Rewrite the question into 2-4 search queries.
2) Call search_docs for each query.
3) Combine evidence.
4) Produce final answer with citations to retrieved chunks.

Output must be:
- "queries": [...]
- "answer": "..."
- "citations": [{"chunk_id": "...", "snippet": "..."}]
