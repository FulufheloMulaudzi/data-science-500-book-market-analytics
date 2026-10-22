BOOK MARKET ANALYTICS (Data Science 500 level) - Fulufhelo Mulaudzi (402601594)
==============================================================================

STEPS (about 10 minutes, mostly waiting for the scrape)
1. In the VS Code terminal:  python -m pip install -r requirements.txt
2. Open BookAnalytics_Assignment/Book_Market_Analytics.ipynb
3. Select your Python kernel (top right), then press Ctrl+Shift+P, type
   "restart kernel and run all" and click "Jupyter: Restart Kernel and Run All Cells".
4. Wait 5-8 minutes. Do not interrupt the scrape.
5. The last cell must show OK for all four files.
6. Submit from the BookAnalytics_Assignment folder:
     Book_Market_Analytics.ipynb, books_clean.csv, Book_Market_Analytics_Report.pdf

NOTE: books_clean.csv and the PDF are created by running the notebook, because the real
website could not be reached from my environment.

VERIFIED: full run with zero errors against a local copy of the site's HTML. The
simplified code gives the SAME cleaned dataset (identical file) and the SAME model
results (to 4 decimal places) as the advanced version.
