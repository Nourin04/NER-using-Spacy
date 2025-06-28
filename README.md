#  Named Entity Recognition (NER) Visualizer




This is a simple and interactive Named Entity Recognition (NER) web app built using **spaCy**, **Gradio**, and **displaCy**. It allows users to input any text and see the named entities (such as people, organizations, locations, dates, etc.) highlighted in real-time.

---

## 🔍 About spaCy and displaCy

### spaCy
[spaCy](https://spacy.io/) is a powerful and fast open-source library for Natural Language Processing (NLP) in Python. It's designed specifically for production use and supports tasks like tokenization, part-of-speech tagging, dependency parsing, and **Named Entity Recognition (NER)**. SpaCy comes with several pre-trained models for different languages, making it easy to extract meaningful insights from raw text.

### displaCy
[displaCy](https://spacy.io/usage/visualizers) is spaCy's built-in visualizer for syntactic dependencies and named entities. It renders text with highlighted entities in a visually appealing way using HTML and CSS, making it ideal for web apps and educational tools.

---

## Demo

![image](https://github.com/user-attachments/assets/697a268b-ffbf-4d98-8b7c-932963842263)


---
## Sample Input
```
Barack Obama was born in Hawaii and served as the 44th President of the United States.
```
---


## Tech Stack

- **spaCy**: NLP engine for Named Entity Recognition  
- **displaCy**: Built-in spaCy visualizer for entities  
- **Gradio**: User-friendly interface for rapid prototyping and sharing ML apps  
- **Python**: Core programming language

---

## Features

- Named Entity Recognition (NER) using `en_core_web_sm` model
- Live entity highlighting with `displaCy`
- Easy-to-use Gradio web interface
- Instant visualization without needing to code

---


