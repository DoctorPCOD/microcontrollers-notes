# Week 9

## Monday
- H-bridge (754410)
  - Pinout explanation
- Control flow: iterative (Section 18.8)
  - `while` (wait for a condition to be met)
    - When to use
    - Syntax
    - Infinite `while` loop

### Activity 11: H-Bridge Motor Driver

## Wednesday
- Lab 8: Proportional & Integral Control

## Friday
- Serial I/O (Chapter 15)
  - Parallel I/O vs. serial I/O
  - Simplex vs. duplex (half and full)
  - Synchronous vs. asynchronous
  - Primary vs. secondary device(s)
  - Secondary configuration
  - Protocols
    - USART
      - Pins
      - `Serial.print`
      - Configuration registers: `UCSR0A`, `UCSR0B`, `UCSR0C`, `UDR0`
      - (Lab 14)
    - SPI
      - Pins
      - Configuration registers: `SPSR`, `SPCR`, `SPDR`
    - TWI
      - Pins

### Activity 12: Serial Communication Protocols on the ATmega328P

---

## Resources
- [Class textbook (PDF)](https://doctor-pasquale.com/wp-content/uploads/2021/02/The-Yellow-Book.pdf)

---

## Topical Outline
- Registers
- Top down software design
- Interrupts and real-time events
- Serial input/output

## Course Objectives Covered
- Apply the principles of top down design to microcontroller software development
- Describe the interfaces for input and output including computer buses, parallel, and serial
- Identify timing issues and events
- Describe different types of memory used in microcontroller systems
