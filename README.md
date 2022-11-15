# TenderHack
## Purpose and task
Development of a prototype of the mechanism for searching for goods on the selection portal

As part of the hackathon, the task to be implemented is: Analyze a typical functional product search system (search in the course of a set of names - hints, contextual synonyms, transliteration, oki, ranking of hints and issuance, search taking into account properties, accounting for word permutation, search history, search for goods and goods ). etc.); Implement the system; Test the system, compiling its work within the framework of the implementation of metrics; About the round performance of the project; Identify opportunities for scaling the solution and propose improvements.

![2022-10-31 23-27-55](https://user-images.githubusercontent.com/92402616/199105142-7a5a1e7a-f3b4-4166-8f26-07c21ee439c9.gif)


## Решение 

![Снимок1](https://user-images.githubusercontent.com/92402616/199107780-f95521fe-7034-4659-ab39-d1f29b6d490d.PNG)

![Снимо2к](https://user-images.githubusercontent.com/92402616/199108041-87c9bdc0-a43c-45f8-a270-a56cf1133111.PNG)



## Technical description of the project

- server.py - Flask backend, connects ML to the front
- search.py - building information search
- nlp.py - nlp processing of datasets and outgoing files
- main.py - ml part with Bert language model
- autocorrect.py - autocorrect source files
- autocomplete.py - autocomplete files at runtime
- template and statics - front part
- bert - language model training


