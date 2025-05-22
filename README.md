NM project

Data Preprocessing

Steps Involved:

1. Text Cleaning:

   * Removed special characters, links, extra spaces.
   * Lowercased text.

2. Tokenization:

   * Used BERT tokenizer to convert text into tokens.

3. Padding & Truncation:

   * Standardized all input lengths (e.g., 128 tokens).
   * Handled with attention masks.

4. Label Encoding:

    Mapped categorical sentiment values to integers.

5. Data Loader Preparation:

   * Split into training and validation.
   * Batched for GPU training.
