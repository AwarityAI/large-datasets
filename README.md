# Public Large Datasets
One of the key limitations of most LLMs is the size of the context window. The context window is basically the size of the window of information that an LLM can reason over. Beyond that size the LLM needs to do various computational tricks e.g. lose information or compress information.

For example Google Gemini claims 1m tokens as a context windo, OpenAI and others are somewhat smaller than this. The novel "War and Peace" is 1.8m tokens. So imagine any dataset as big as "War and Peace" and know that any modern LLM cannot truly reason over it without losing information.

Awarity uses a patent-pending algorithm, the Elastic Context Window, to bypass this limitation. This repository contains some of our recent explorations using publicy available information.
