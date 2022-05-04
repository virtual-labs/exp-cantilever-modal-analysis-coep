### Procedure

1. Please read General Theory and Background related to this experiment.
This section explains the experimental set-up, procedure, observations and analysis related to the experiment.

2. **Experimental set-up**\
A. **Apparatus:**

Following apparatus will be used to perform the real experiment:
a.Impact Hammer
b.Accelerometer
c.Multi-channel Vibration Analyzer (At least two-channel)
d.A PC or a Laptop loaded with software for modal analysis.
e.Test-specimen (A cantilever held in a fixture)
f.Power supply for the PC and vibration analyzer, connecting cables for the impact hammer and accelerometer, fasteners and spanner to fix the specimen in the fixture, and adhesive/wax to fix the accelerometer).

**B. Brief information about the important apparatus used in real experiment:**
**a.Impact Hammer:** This looks like an ordinary hammer but its head is fitted with a load cell and contains electronic circuitry and an out put cable that can be connected to vibration analyzer. On hitting the impact hammer on any structure an impulsive force is applied to the structure which is a cantilever in our case. An equal and opposite force is sensed by the load cell fitted in the head of the hammer. This generates an electric signal that is given to vibration analyzer which analyzes the signal, compares with the signal received from accelerometer fixed o the structure, nd this information is used to develop FRF (Frequency Response Function) and finally the natural frequencies of the structure are found.

**b.Accelerometer:** An accelerometer is a device (a transducer) which when attached to a vibrating structure gives out electric signal proportional to the acceleration. This signal is given to a vibration analyzer which processes and analyzes the signal. In case of this experiment, the signal coming from accelerometer fitted to the cantilever is analyzed with respect to the one received from the impact hammer in order to find the natural frequencies of the cantilever.

**c.Vibration Analyzer:** Vibration Analyzer is an electronic device that processes and analyzes the signals received fro transducers used in vibration measurement like impact hammer, accelerometer, digital tachometer, etc. It has number of channels, i.e. it can receive number of electric signals simultaneously. Four-channel vibration analyzer is quite common. The vibration analyzer has very sophisticated electronic circuits and works together with a computer. Fast Fourier Transform (FFT) is an algorithm frequently used for analysis of the electric signals which provide frequency components and their corresponding amplitudes present in the signals.

**d.A PC or a Laptop loaded with a software for modal analysis:** In addition to the software used alongwith the vibration analyzer, softwares are available now-a-days devoted exclusively to the modal analysis. Such softwares facilitates inputting data to the computer related to geometry of the structure, location of fixing of the accelerometer on the structure as well as points of hitting of the impact hammer, their directions, and so on. Also, there are facilities to select type of analysis required, ranges of various parameters of interest, and so on. Such softwares essentially process the signals received from the impact hammer and accelerometer, carrying out their FFTs, finding FRF, obtaining Mode Indicator Function, carrying out curve fitting over a selected range of frequencies, and finally providing the natural frequencies, mod shapes, and modal damping factors.

**e.Fixture and Test-Specimen:** A fixture holds the Steel bar of rectangular cross section firmly at one end so that the specimen can be considered as a cantilever. The cross sectional dimensions of the cantilever are 11.8 x 3.175 mm and length 150 mm. The fixture holds the bar firmly at one end and the fixture rests on a table. A small (miniature) accelerometer is attached at the point, marked as node 5, using an adhesive, Locktite.

**3. Procedure - Real experiment**
**a.   Prepare the cantilever:** Measure the length on the fixture that holds the steel bar and leave a margin of that length on the steel bar. Divide the remaining length of the steel bar into six parts and mark node numbers at each division - from 1 through 7. Let node 7 be the free end and node 1 the fixed one. Fix the accelerometer to the steel bar at node 4 but on the face of the bar opposite to the markings. Ensuring that face of bar with markings and node numbers up, fix the bar into the slot on the fixture so that a cantilever is formed.
**b.   Connect the wires and cables:** Make connections of the vibration analyzer, PC or laptop, accelerometer and the impact hammer as given in the manuals or under guidance of experts.
**c.   Switch on the power supply. Open the softwares of vibration analysis and experimental modal analysis installed on the PC/laptop. Provide necessary inputs and make necessary settings in the softwares. Ensure that there is proper supply and communication between the devices connected.
d.   Now we shall provide impacts by the impact hammer on the nodes marked on the cantilever one by one. Impacts will be given on nodes 2, 3, 4, 5, 6, and 7; node 1 is fixed. Accelerometer is connected at node 5. Signals from the impact hammer and the accelerometer will be received by the vibration analyzer for each impact provided one by one and will be compared and analyzed by the softwares. Curve known as Frequency Response Function (FRF) will be generated by the software that is used to find the natural frequencies of the cantilever.
e.   Observe the curve and read frequencies that correspond to peaks of the FRF.

**4. Procedure - Virtual experiment**
A cantilever will be seen on the screen of your PC, held in a fixture at one end, thereby making its one end fixed. It is divided into six equal parts and seven points are marked from 1 to 7 due to this division. An accelerometer is seen fixed at point 5. Point 7 is at free end. The point at which the hammer is to be hit can be selected by choosing it from the button 'choose' and the hit can be performed by clicking on the button 'hit'. Dimensions and material of cantilever are given. The FRF is displaced in the window after every hit. At the end Mode Identification Function is seen from which the natural frequencies can be identified. Follow the steps given below to find the natural frequencies of the cantilever by impact test:
a. Choose point 2 from the button for the hit; the hammer will move just above that point. Perform the hit by clicking on the button 'hit'. The cantilever will be seen vibrating for some time and corresponding FRF (input at point 2 at which hammer is hit and output from point 4 at which the accelerometer is fixed) will be displayed in the window.
b. Repeat step 'a' for hits at all other points from 3 to 7.
c. Click on the button 'obtain FRF'; Modal indicator Function will be displayed.
d. Observe the graph marking frequencies corresponding to the peaks. The peaks correspond to the natural frequencies.

**5. Observations and analysis:**
1. Observe FRF (Mode Identification Function)
2. Note the frequencies that correspond to the peaks of amplitude. These correspond to the natural frequencies of the cantilever. In fact, they correspond to the natural frequencies of the principal modes of the cantilever that were excited, or participated in vibration of the cantilever due to impacts.
3. Compare these values with those obtained from formulae given in the 'background' of this experiment
4. Ponder on the difference in values obtained from these two sources - Experimental and Analytical.
