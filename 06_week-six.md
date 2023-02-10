# Week 6

## Monday
- Control flow: conditional (Section 18.7)
  - `if` review
  - Switch case
    - When to use
    - Syntax
- Watchdog timer
  - What is it
  - What it can do
    - Trigger an interrupt and reset
    - Reset only
  - How to configure it
    - `WDTCSR`

## Wednesday
- Lab 5: External Interrupts
  - [Lab 5 website](https://doctor-pasquale.com/microcontrollers-lab-5/)

## Friday
- System clock
  - What is a clock
  - Clock sources on the ATmega328P
    - Internal 8 MHz
    - Internal 128 kHz
    - External crystal
    - External clock
  - Clock signals (I/O, ADC, etc.)
  - Prescalers
- Timer/counters
  - Description of each
    - Name
    - Resolution
  - Things to do with timer/counters
    - Trigger periodic interrupts
    - Create a waveform
  - Normal mode
    - Equation of operation
  - CTC mode
    - Equation of operation
  - How to use timer/counters
    - `TCCRxA`, `TCCRxB`, `TCCR1C`, `OCRxn`, `TCNTx`

### Activity 8: I/O Clock Frequency

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
