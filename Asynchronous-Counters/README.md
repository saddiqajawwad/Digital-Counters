# Asynchronous Counters – DLD Project

This folder contains a set of asynchronous counter designs created and simulated using NI Multisim.  
These counters demonstrate the behavior and implementation of asynchronous (ripple) counters using JK flip-flops.

## Counters Included

1. **3-bit Up Counter**  
   - A basic 3-bit asynchronous up counter.  
   - Counts from 0 to 7.

2. **Mode-6 Counter**  
   - Asynchronous counter configured to cycle through 6 states (0 to 5).  
   - Demonstrates modulus operation in asynchronous counters.

3. **4-bit Bidirectional Ripple Counter**  
   - Can count both up and down from (0 to F).  
   - Asynchronous design using flip-flops to illustrate bidirectional counting.

4. **Mode-5 Counter**  
   - Asynchronous counter cycling through 5 states (0 to 4).  
   - Demonstrates custom modulus design.

5. **Mode-6 Counter (3 to 8)**  
   -  Counts from 0 to 8 on first run, then starts from 3 on subsequent runs. 
   - Illustrates non-zero start count and modulus in asynchronous counters.

## How to Use
1. Open the `.ms14` files in NI Multisim.  
2. Run the simulation to observe each counter’s output and behavior.  
3. Each file is named clearly according to its type and mode.

## Notes
- NI Multisim is required to open and simulate the circuits.  
- This README complements the main repository README by providing detailed information specific to asynchronous counters.
