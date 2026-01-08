# Digital Clock – DLD Project

This folder contains a **2-minute asynchronous digital clock** designed and simulated using NI Multisim.  
The clock uses **JK flip-flops** to implement the counting mechanism asynchronously.

## Clock Description

- The clock counts from **0:00** to **1:59** (total 2 minutes) in a standard minute-second format.  
- Implemented using asynchronous counters for minutes and seconds.  
- Demonstrates the behavior of **JK flip-flops** in a real-time digital application.  
- Includes preset and reset logic to correctly start and end the 2-minute timing cycle.

## How It Was Designed

1. Asynchronous counters were used to generate seconds and minutes.  
2. JK flip-flops were connected in a ripple configuration to handle counting.  
3. Logic gates were used to **reset the counters** after 1:59 to 0:00.  
4. The simulation allows observation of the clock running for the full 2 minutes.  
   - For demonstration purposes, simulation speed can be adjusted to shorten viewing time.

## How to Use

1. Open the `.ms14` file in NI Multisim.  
2. Run the simulation to observe the clock counting from 0:00 to 1:59.  
3. Adjust the simulation speed if needed to view the full timing cycle.

## Notes

- NI Multisim is required to open and run the simulation.  
- Additional documentation such as screenshots or demo videos may be added later.
