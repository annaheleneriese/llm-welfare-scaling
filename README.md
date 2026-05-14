# Beyond Left and Right: Measuring Ideological Change in Danish Parliament Debates through LLM-Based Text Scaling (2009–2025)

Master thesis code - MSc Business Administration and Data Science, Copenhagen Business School, 2026.

## Notebooks

Run in order:

1. **01_classifiers.ipynb** — Data collection, preprocessing, welfare speech classification, and ideology classifier
2. **02_pairwise_comparison.ipynb** — LLM-based pairwise comparison and Bradley-Terry scaling
3. **03_analysis.ipynb** — validation, descriptive and explanatory analysis of ideological change
4. **04_validation_tests.ipynb** — additional validation

## Setup

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Create a `.env` file based on `.env.example` and add your API keys:
   ```
   OPENAI_API_KEY=your_key_here
   MANIFESTO_API_KEY=your_key_here
   ```

## Requirements

- Python 3.x
- API access to OpenAI (GPT-4o-mini) and the Manifesto Project
