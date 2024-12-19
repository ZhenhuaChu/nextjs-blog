---
title: 'How to add text at Start and End of Every Line in VS Code'
date: '2024-12-18'
---

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
Steps: 
1. Ctrl + F
2. Use Regular Expression
3. Search ^(.+)$
4. Replace '$1', 5. Replace all
