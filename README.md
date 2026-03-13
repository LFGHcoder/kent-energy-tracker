# Kent State Campus Walk Energy Tracker

Language: C++

This program simulates a student walking 150 steps across campus while tracking their energy level.

The student starts with **100 energy points**, and the energy changes depending on the step number.

Rules used:
- Fibonacci steps → **Energy Boost (+10)**
- Step divisible by **3 and 5** → **-5 energy**
- Step divisible by **3** → **-2 energy**
- Step divisible by **5** → **-3 energy**
- Otherwise → energy stays the same

If the energy drops below **50**, the program prints:

Low Energy! Consider getting coffee.

The program prints the step number and the student's energy after every step.
