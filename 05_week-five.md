# Week 5

## Monday
- `SREG` (Chapter 6)
- Interrupts (Chapter 13)
  - Program flow: polling vs. interrupts
  - Interrupt service routines
  - Interrupt sources on ATmega328P
    - Asynchronous
    - Synchronous
  - `reset`
  - Global interrupt masking
    - When setting up a peripheral
    - Doing critical comparison operations

## Wednesday
- Lab 4: Sensors and Sensor Calibration

## Friday
- External interrupts
  - `INT0` (D2) and `INT1` (D3)
  - Trigger conditions
  - Registers: `EICRA` and `EIMSK`
- Pin change interrupts
  - `PCINT0` (port B), `PCINT1` (port C) and `PCINT2` (port D)
  - Trigger conditions
  - Registers: `PCICR`, `PCMSK0`, `PCMSK1` and `PCMSK2`
  - Why these take extra work

### Activity 6: External and Pin Change Interrupts

---

## Resources
- [Class textbook (PDF)](https://doctor-pasquale.com/wp-content/uploads/2021/02/The-Yellow-Book.pdf)

---

## Topical Outline
- Registers
- Top down software design
- Interrupts and real-time events

## Course Objectives Covered
- Apply the principles of top down design to microcontroller software development
- Describe the interfaces for input and output including computer buses, parallel, and serial
- Identify timing issues and events
- Describe different types of memory used in microcontroller systems
