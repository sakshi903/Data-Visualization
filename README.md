# Data-Visualization
Topic: Dashboard of the Data Visualization by using Tkinter and export the graph as per the requirements.

In this project i created two file one for data visualization and ploting the data into the Graph.
Second file is all about representing the graph (which are creted by first file) into the GUI Interface.

For the First File (CovidDataRepresentationUsingGraph.ipynb)
I used below Libraries: --> 
pandas
matplotlib.pyplot
subprocess

Pandas is Python's popular data analysis library, it provides several different functions to visualizing our data with the help of the . plot() function. 
There is one more advantage of using Pandas for visualization is we can use data analysis functions and plotting functions.
I used .plot function to plot the data.
I used .read_csv function to read the data from the csv file.

Matplotlib is a Python library that helps in visualizing and analyzing the data and helps in better understanding of the data with the help of graphical, pictorial visualizations that can be simulated using the matplotlib library. 
Matplotlib is a comprehensive library for static, animated and interactive visualizations.
I used,
plot() -- It creates the plot at the background of computer, it doesn’t displays it. We can also add a label as it’s argument that by what name we will call this plot – utilized in legend()
xticks() --	It decides how the markings are to be made on the x-axis.
xlabel() --	it labels the x-axis
ylabel() -- it labels the y-axis
title()	-- it gives the title to the graph
figure(figsize = (x, y) -- whenever we want the result to be displayed in a separate window we use this command, and figsize argument decides what will be the initial size of the window that will be displayed after the run
legend() --  used to Place a legend on the axes.
ioff() -- used to turn the interactive mode off. Parameters: This method does not accepts any parameter. Returns: This method does not return any value
grid() -- sets the visibility of grids by specifying a boolean value (True/False).
savefig() --  used to save the figure created after plotting data. The figure created can be saved to our local machines by using this method.

subprocess module allows you to spawn new processes and obtain their return codes. 
This module intends to replace several older modules and functions.
The subprocess module provides a function named call. 
I hve used call function.
This function allows you to call another program, wait for the command to complete and then return the return code.


For the Second File (GUIFrame.ipynb)
I used below Libraries: --> 
tkinter
from tkinter i imported ttk
from PIL i import ImageTk, Image

Python offers multiple options for developing GUI (Graphical User Interface). Out of all the GUI methods, tkinter is the most commonly used method. 
It is a standard Python interface to the Tk GUI toolkit shipped with Python. 
Python with tkinter is the fastest and easiest way to create the GUI applications.
The primary GUI toolkit we will be using is Tk, which is Python's default GUI library. 
We'll access Tk from its Python interface called Tkinter (short for Tk interface).
Tk() to display the root window and manages all the other components of the tkinter application

Canvas() -- Canvas is a rectangular area intended for drawing pictures or other complex layouts. You can place graphics, text, widgets or frames on a Canvas.
label() -- Tkinter Label is a widget that is used to implement display boxes where you can place text or images. 
The text displayed by this widget can be changed by the developer at any time you want. 
t is also used to perform tasks such as to underline the part of the text and span the text across multiple lines. 
It is important to note that a label can use only one font at a time to display text. To use a label, you just have to specify what to display in it (this can be text, a bitmap, or an image).
frame() -- Frame used to organize the group of widgets. It acts like a container which can be used to hold the other widgets. 
The rectangular areas of the screen are used to organize the widgets to the python application.
Scrollbar() -- This widget provides a slide controller that is used to implement vertical scrolled widgets, such as Listbox, Text and Canvas. 
Note that you can also create horizontal scrollbars on Entry widgets.

PIL --> Tkinter relies on the Python Pillow (aka PIL) package for image processing capabilities. 
Using Pillow, a Tkinter function that displays a text-based message can instead display an image-based message.
(Note that depending on the purpose of an image in a Tkinter application, different coding may be required.)

Imagetk module contains support to create and modify Tkinter BitmapImage and PhotoImage objects from PIL images.\

