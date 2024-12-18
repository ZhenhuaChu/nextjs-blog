---
title: 'Reading Notes of What Are ChatGPT and Its Friends'
date: '2024-09-13'
---

## What Are ChatGPT and Its Friends?

What can ChatGPT do?

Simple tasks: Write a letter; make up a story, write descriptive entries for products in a catalog etc.

Middle tasks: Generate a list of terms for search engine optimization, a reading list on topics you're intrerested in, write a book etc.

Tough tasks: Write software, explain code including code that has been intentionally obfuscated, pretend to be an operating system, a text adventure game etc. 


What is ChatGPT?

ChatGPT is some kind of an AI bot that has conversations. Itself is not a LLM. It's a UI build around one specific language model GPT 3.5/4.0. 

## How to add text at Start and End of Every Line in VS Code

Text before
```
Test1
Test2
Test3
```
Text after
```
'Test1',
'Test2',
'Test3',
```
Steps: 1. Ctrl + F 2. Use Regular Expression 3. Search ^(.+)$ 4. Replace '$1', 5. Replace all
