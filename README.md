# CRC Project 2
Projecto 2 - Racial Segregation using Thomas C. Schelling Model

---

## Grupo 15
- 89905, João Gomes
- 98649, Pedro Guerra
- 98668, Ricardo Gonçalves

----

## Code Overview

#TODO: 

---

## Dependencies
- tkinter (in Python 3.1 or superior)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [numpy](https://pypi.org/project/numpy/)

---

## Installation and execution

1. Clone this repository

```bash
git clone https://github.com/siimplex/crc-project-2.git
```

2. Open a terminal and install the dependecies

```bash
pip install -r requirements.txt
```

3. Run the program

```bash
cd src
python main.py
```

### Demo 

![execution example](https://github.com/siimplex/crc-project-2/blob/main/demo.png "Program Window")

Parameters:

- **Number of Iterations**: integer less or equal than 0 will run indefinitely else the number in the text box is used;
- **Population Width**: number of columns in the board;
- **Population Height**: number of lines in the board;
- **Neighbourhood Depth**: the radius of each individual's neighbourhood;
- **Similarity Threshold**: float number between 0.0 and 1.0;
- **Toggle Random**: button that toggles between random ratios and user inputted ratios;
- **Empty Ratio**: the ratio of empty spaces, float number between 0.0 and 1.0;
- **Races Ratios (A-E)**: the ratios of the races, float number between 0.0 and 1.0;

Buttons:

- **Load**: load a new board based on the paramaters;
- **Start**: starts the simulation, and runs for the number of iterations or indefinitely;
- **Step**: runs a single iteration of the simulation;
- **Stats**: shows a popup with the number of individuals and number of neighbours based on it's race;

---

### References
- Schelling, T.C., [Dynamic models of segregation](http://norsemathology.org/longa/classes/stuff/DynamicModelsOfSegregation.pdf). Journal of Mathematical Sociology, 1971. 1(2): p. 143-186
- McCown, F.  ["Schelling's Model of Segregation"](http://nifty.stanford.edu/2014/mccown-schelling-model-segregation/) (2014).
- Hart, V. and N. Case. [Parable of the polygons](https://ncase.me/polygons/): A playable post on the shape of society.
- Sheong, S. [Simulating racial segregation with Go](https://towardsdatascience.com/simulating-racial-segregation-with-go-6224c253a1d2) (2019)
- Moujahid, A. [An Implementation of Schelling Segregation Model using Python and Streamlit](http://adilmoujahid.com/posts/2020/05/streamlit-python-schelling/) (2020)
- Moujahid, A. [An Introduction to Agent-Based Models: Simulating Segregation with Python](https://www.binpress.com/simulating-segregation-with-python/) (2020)
- Liu, Y.T. [The Schelling Model of Segregation: Static and Dynamic Equilibrium](https://ytliu0.github.io/schelling/) (2017)
- [Schelling’s Segregation Model](https://python.quantecon.org/schelling.html)
- [tkinter documentation](https://docs.python.org/3/library/tkinter.html)
- [matplotlib documentation](https://matplotlib.org/3.3.3/contents.html)
