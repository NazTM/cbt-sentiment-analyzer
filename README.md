# CBT Cognitive Distortion & Sentiment Analyzer

This Python script leverages pre-trained language models and regex patterns to help users identify common cognitive distortions in their thoughts and understand the overall sentiment expressed.

## Features:

Cognitive Distortion Detection: Uses regular expressions to detect classic thinking errors like all-or-nothing thinking, catastrophizing, personalization, and more.

Sentiment Analysis: Employs a pre-trained DistilBERT model fine-tuned for sentiment classification to automatically label inputs as positive or negative with confidence scores.

Refined Emotional Reasoning Detection: Special handling for “I feel...” statements, ignoring neutral feelings such as “okay” or “fine” to reduce false positives.

Interactive User Input: Accepts user thoughts interactively with an option to exit the program.

Reframe Suggestions: Provides helpful suggestions to rethink and challenge detected distortions.
