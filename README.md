# Honduras IMF Report Analysis

This notebook analyses Honduras’s 2023 IMF Article IV report using Gemini, MiniLM embeddings and FAISS. It generates summaries, financial indicators, thematic counts, RAG comparisons and a four-panel dashboard.

## Run in Google Colab

1. Download the [IMF report](https://www.imf.org/-/media/files/publications/cr/2023/english/1hndea2023001.pdf), rename it `honduras_pdf.pdf`, and upload it to Colab.
2. Add your Gemini API key to Colab Secrets as `Gemini` and enable notebook access.
3. Run all cells in order. Required packages install automatically.

Outputs are saved in `honduras_analysis/results/`. The final cell downloads a ZIP containing the results.

## Limitations

Tier 1 capital remains missing. The unemployment extraction selected an older observation, and judge scores require source verification.

## License

See `LICENSE` for the code’s MIT License. The IMF document retains its original terms.
