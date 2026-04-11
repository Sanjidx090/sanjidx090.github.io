#  Deep reasearch prompt
```Activate Deep Web Search. I am building a research library to understand **tokenizers** and exactly how they impact the **reasoning capabilities** of LLMs (like why they fail at math, spelling, or logic puzzles). We are starting from the basics.

Your task is to scour the internet and compile a structured syllabus with direct, clickable URLs to high-quality resources. Do not hallucinate links; verify they exist. 

Please search for and provide the following categories, giving a 2-sentence summary for each link explaining why it is relevant:

1. **Foundational Videos:** - Search YouTube for the best visual and practical breakdowns of tokenization. Specifically, find Andrej Karpathy's "Let's build the GPT Tokenizer" and 3-6 other highly-rated beginner videos on LLM tokenization. Provide the direct YouTube URLs. 

2. **Core Academic Papers (arXiv/PDFs):** - Search for the foundational papers on Byte-Pair Encoding (BPE), SentencePiece, and token-free models (e.g., ByT5). 
- Search for recent papers discussing how tokenization negatively impacts LLM reasoning, math, and character-level logic. Provide direct arXiv or PDF links.

3. **GitHub Repositories:** - Find and link the most relevant GitHub repos for someone wanting to see the code behind tokenizers. Include links to `openai/tiktoken`, `karpathy/minbpe`, and `huggingface/tokenizers`.

4. **Articles & Blog Posts:** - Search for accessible web articles explaining the "quirks" of tokenizers. Find the "SolidGoldMagikarp" article on LessWrong (about glitch tokens) and 1-10 interactive tokenizer web tools (like Tiktokenizer). Provide the direct URLs. 

5. **A 5-Step "Start Here" Guide:** - Based on the links you just found, tell me exactly which 10 links I should click first to go from zero knowledge to understanding the tokenizer-reasoning bottleneck.```
