# Prompt Engineering Basics for Quant Analysts

This guide introduces effective prompt engineering practices for quantitative research workflows using generative AI (like ChatGPT or Claude). It is part of the **GenAI for Quant Productivity** project.

---

## 1. Role prompting

Always start by defining the AI’s role clearly to receive domain-specific responses.

### Example:

You are a quantitative research analyst working on alpha strategy testing using Python and Pandas.


---

## 2. Structured prompts

Use bullet points or numbered steps in your input to get structured answers.

### Example:
Ask like this:

You are a quant researcher. Given:
  1. Input: CSV of historical stock prices
  2. Task: Calculate volatility using 20-day and 50-day rolling windows
  3. Output: Line chart comparing both volatilities, with interpretation


Instead of:
> How do I calculate volatility?

This helps ChatGPT respond more like a real research teammate.

---

## 3. Output formatting

Ask the AI to format output cleanly: e.g., with markdown, tables, or comments in code.

### Example:
Give me the results in a markdown table. Add inline comments to the Python code.


---

## 4. Iterative refinement

If the first output isn’t perfect, refine your prompt by:
- Clarifying assumptions
- Providing sample input/output
- Asking for step-by-step breakdowns

---

## 5. Systematic naming

Save prompts with meaningful filenames, like:
- `alpha_signal_generation_v1.txt`
- `risk_parity_optimizer_prompt.md`

Helps build a reusable library of prompt assets.

---

## 6. Use AI for non-coding tasks too

Prompt AI to help with:
- Literature review summaries
- Research documentation
- Backtest report generation
- Explaining quant terms in simple language

---

## 7. Prompt as documentation

Well-crafted prompts themselves become reusable documentation of your workflow. You can include them in:
- Your GitHub repos
- Internal Notion/wiki docs
- Research notebooks

---

## 8. Grounding for accuracy

If output seems vague or incorrect, ground the model by providing:
- Real data
- Formulas
- Context about your use case

---

## 9. Prompt logs

Maintain a record of prompt–response pairs that worked well, especially for:
- Coding/debugging tricks
- Data cleaning workflows
- Interview answers

You’ll use them again.

---

## 10. Ethics + limits

Always verify outputs from LLMs. Never treat results as financial advice or publish model output without human review. Use AI as a tool, not a decision-maker.

---

Created as part of the [genai-quant-productivity](https://github.com/yourusername/genai-quant-productivity) repository.
