# Project 2: Build an LLM 

## 🌟 Highlights

- Python is required
- LLM_exercises.ipynb features all the exercises from the book, Build a Large Language Model (from Scratch) by Sebastian Raschka
- Also included is some work on additional training from publicly available texts
- User_interface folder features code to run the trained model 


## ℹ️ Overview

For my project I wanted to take what I could learn from the book, Building a Large Language Model from Scratch, and expand on that with additional training using documents available on Project Gutenberg and Wikisource to make a more advanced model myself. I had a hard time figuring out a way to easily get these documents as plain text files with none of the extra headers and footers from the websites. On the Github repository for the book there is a section on getting data from Project Gutenberg, however the repository the author links to for this is made to run on Mac or Linux, and I failed at figuring out how to make that work for my Windows computer. I instead downloaded various texts from Project Gutenberg to txt files and saved them in a folder to run through them for training, code for this can be found in the user_interface folder, “additional_model_training.py”.


## 🚀 Using on Jupyter Notbook

After cloning this repository, the following commands need to be entered into the terminal:

```bash
pip install -r requirements.txt
```
I chose to run this using Pixi environment, to do so you will need to run the following commands (ensure that the pixi.toml file in it your oot folder)
```bash
powershell -ExecutionPolicy ByPass -c "irm -useb https://pixi.sh/install.ps1 | iex"
```
```bash
pixi install
```
Finally, you can launch Jupyter Lab to access the notebook using:
```bash
pixi run jupyter lab
```


## ⬇️ Running the User Interface

To run the user interface 


```bash
pip install chainlit
```
OR
```bash
pip install -r requirements-extra.txt
```
Then launch the program with
 
```bash
chainlit run app_orig.py
```

It should open a new tab in the browser on localhost:8000

