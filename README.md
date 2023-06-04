# **WARNING! This program may no loanger be useable due to it being a timed project. The code is available for reference only!**

# EPB-Heating-Unit-Type
Python program used by EPB to determine if a customer is using an electric or non-electric heating unit.

## Installation Guide
The final installation procedures will be decided by EPB at the time of implementation, based on
how EPB has decided to integrate this tool. As of the end of Spring 2023, the product is available in
the form of a simple downloadable executable file. This file should be immediately launchable.
Dependencies and packages will be automatically unpacked/installed on the first run. Users/installers will
be alerted via Command Line to expect a slightly delayed run upon the executable’s first launch.

## User's Guide
To run the current version of the program, follow the steps below:
1. Install dependencies (if not already installed):
   a. Latest Python
   b. Python libraries
      i. Matplotlib
      ii. Numpy
      iii. Pandas (normally included with NumPy)
      iv. Statistics module
      v. MySQL-Python connector
      vi. SQLAlchemy
2. Open terminal/command prompt in the directory containing *SingleExecutable.py* and/or *BatchExecutable.py*

## **SingleExecutable**

3. Execute: *python ./SingleExecutable.py*
4. The user will now be prompted to input a premise ID. This is the ID of the EPB meter.
5. Once the premise ID is enteres, a visual will appear displaying a graph as described below.
   a. **Left y-axis**: Temperature (celcius)
   b. **Right y-axis**: power consumption (kilowatt per hour)
   c. **X-axis**: Time (months)
   d. **Blue line**: temperature
   e. **Red line**: power consumption
6. To close the program, simply close the window containing the graph.

## **BatchExecutable**

3. Execute: *python ./BatchExecutable.py*
4. The program runs without a progress bar.
5. Once the program is finished, it will print the amount of time it took to complete.
