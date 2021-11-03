# Simple-Tkinter-GUI-for-experimental-data
Simple Tkinter  GUI for extracting and visualizing experimental transport measurements


Transport measurement performed in low temperatures require scientific software such as LabView for the storage of the data. However the data are often stored in an
unconventional way that makes their visualization and analysis very time-consuming. This is a simple Tkinter app for the quick visualization of experimental data.

Guidelines 

1. Download and extract the data to a folder. Change the path variable in the code to the path where you saved your data.
2. After running the code in the tkinter frame click on the folder dropdown and select a folder (for example 2019-09-11#012) and click the button select folder.
3. From the select x axis menu chose the column for the x_axis (for example aux1) and click the button select x.
4. From the select y axis menu chose the column for the x_axis (for example lockin/R) and click the button select y.
5. Now the data for the chosen data set are selected and you can plot them by clicking the plot button.
6. If you want to further explore the data, you can click again the buttons select x and select y.
7. If you want to choose only one of the two sweeps, press One way. Now the plot shows only the one way.
8. Again click the select buttons and if you want to reduce the noise of the signal enter an odd number for window_length (for example 11) and a smaller number for
   the polynomial order (for example 3) and press the filter button. Now when you plot the data the noise will be reduced significantly.
9. Remember to always click the select buttons when you change a value from the dropdown menues.
