# Telling AI What It Doesn't Know: From NLP to RAG

## Overview

RAG is a common industrial framework for developing AI-based applications: search over company docs, support bots, compliance Q&A, internal copilots. This session walks through how that kind of setup actually works.

We’ll cover why language has to be processed, how talking to AI turns your words into numbers and vectors, and how the model answers you in text again. Then we look at what happens in real deployments: the model can sound sure and still be wrong. That’s hallucination, and in industry it’s not a minor issue. Wrong answers can mean bad decisions, bad customer advice, or bad code in live systems.

RAG is one standard way teams reduce that risk: retrieve from your knowledge bases and libraries, then generate from that context. We’ll close with a hands-on exercise so you can try the pipeline yourself.

## Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/modafarshouha/mini-rag-workshop/blob/main/rag_workshop.ipynb)

Everything runs in your browser. **There is nothing to install.** You need a laptop, an
internet connection, and a Google account.

## Start here

1. Click the **Open in Colab** button above.
2. Click **Copy to Drive**. This gives you your own copy. Without it, your work is not
   saved.
3. Run the first cell and wait for it to print **SETUP OK**.

If you see a warning that says *"This notebook was not authored by Google"*, that is
normal. Click **Run anyway**.

## What you will build

A small program that reads a college handbook and answers questions about it, in three
steps: **Embed** the text into numbers, **Search** for the closest numbers, **Answer**
using what was found.

You do not need to write any code. Every cell already works. Your job is to read it,
guess what it will do, run it, and see whether you were right.
