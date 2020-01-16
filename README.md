# Console Histogram

For the second assignment, you will get a chance to do some more programming in Java by implementing a histogram viewer. The input (specified below) will be fed into your program via standard input (stdin). Your program should then display a histogram of the data, rendered in the console. You can think of this kind of like a very basic form of ASCII art. You are encouraged to be creative in both your design of the program and the display of the histogram. Along with the histogram, you should also display the minimum, maximum, and mean. Feel free to display other relevant information or statistics along with the histogram.

### Program - Minimum Requirements
  1. Read from stdin the specified input
  2. Display a histogram of the data
  3. Display minimum, maximum, and mean
  4. Exit (program terminates once it has finished rendering i.e. does not wait for a key to be pressed)

### Project - Requirements
  1. All `.java` files should be inside the `/src/` directory.

## Input Specification
Input will be fed to your program through standard in. Each item that is provided will be separated by a space. The input will always be provided in the following order.
  1. The number of bins the histogram should have.
  2. Each data point (space separated again). 

You have been provided with a text file with the smaller data set below and also a large one that includes most NBA players. An example input is inside a file named `nba_heights_sample.txt` along with histograms of what the data should look like when plotted.

```
7 81 82 75 73 74 74 79 72 84 80 77 73 77 81 80 82 75 77 81 80 82 71 79 79 80 77 77 73 72 75 74 83 78 76 79 73 81 81 82 73 82 76
```
This histogram for this should resemble the following (note that since yours will be rendered in a console, it will not look exactly like this. You can use this as a reference for how you are progressing by comparing the bins and the height of the bars):

![Histogram image](https://raw.githubusercontent.com/cgburgess/histogram-java/master/data/7_bins_sample_data.png?token=ACEV5YSRFU3RPDPCKWOH4526FEFIU)
