# Self-test quiz

1. `pip install pymupdf anthropic` then `python extract_questions.py your.pdf` -> creates `questions.json` and `images/`.
2. Open `questions.json` and check any question the script flagged as uncertain.
3. Try locally: `python -m http.server` and open http://localhost:8000
4. Publish: push this folder to a GitHub repo -> Settings -> Pages -> Deploy from branch `main` / root.
   Your quiz will be at https://<username>.github.io/<repo>/
