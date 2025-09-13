# Python Plagiarism checker

This repo consists of a source code of a Python script which detects plagiarism in a textual document using **cosine similarity**.


You might be wondering how plagiarism detection on textual data is done, well it ain't as complicated as you may think.

We all know that computers are good with numbers; so in order to compute the similarity between two text documents, the textual raw data is transformed into vectors => arrays of numbers and from that, we make use of basic knowledge of vectors to compute the similarity between them.

This repo contains a basic example on how to do that.


To get started with the code on this repo, you need to either *clone* or *download* this repo into your machine as shown below;

```bash
git clone https://github.com/Kalebu/Plagiarism-checker-Python
```

## Dependencies

Before you begin playing with the source code, you might need to install dependencies just as shown below;

```bash
pip3 install -r requirements.txt
```

## Running the App

To run this code you need to have your textual documents in your project directory with the **.txt** extension. When you run the script, it will automatically load all the documents with that extension and then compute the similarities between them as shown below;

```bash
$-> cd Plagiarism-checker-Python
$ Plagiarism-checker-Python-> python3 app.py
('2.txt', '3.txt', 0.5465972177348937)
('1.txt', '2.txt', 0.14806887549598566)
('1.txt', '3.txt', 0.18643448370323362)

```


