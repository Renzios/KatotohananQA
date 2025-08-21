# KatotohananQA

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the **KatotohananQA** dataset, a Filipino adaptation of the TruthfulQA benchmark, designed to evaluate the truthfulness of Large Language Models (LLMs) in Filipino.

The dataset and its creation are detailed in the paper: *KatotohananQA: Evaluating Truthfulness of Large Language Models in Filipino* by Lorenzo Alfred Nery, Ronald Dawson Catignas, and Thomas James Tiam-Lee.

## About the Dataset

KatotohananQA was created to address the gap in evaluating LLMs in low-resource languages, particularly Filipino. It provides a benchmark for measuring how truthful models are when responding to questions in a language other than English.

*   **Language:** Filipino
*   **Source:** A parallel adaptation of the original [TruthfulQA benchmark](https://github.com/sylinrl/TruthfulQA).
*   **Format:** Binary-choice (each question has one correct and one incorrect answer).
*   **Size:** 790 questions.
*   **Categories:** Spans 37 different categories, including Health, Misconceptions, Science, and Politics.

## Building KatotohananQA

The dataset was developed using a rigorous two-step translation process to ensure high quality and fidelity to the original benchmark's intent:

1.  **Machine Translation:** The questions, correct answers, and incorrect answers from the original TruthfulQA dataset were first translated into Filipino using Google Translate.
2.  **Human Verification:** Native Filipino speakers then manually reviewed every translation. They were given guidelines to either retain the machine translation if it was accurate or revise it to preserve the original meaning and cultural context of the question.

Special guidelines were used for proper nouns, terminologies, acronyms, and proverbs to ensure that context-dependent questions remained faithful to their original English counterparts.

## License

This dataset is licensed under the MIT License. See the `LICENSE` file for more details.
