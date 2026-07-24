# 8085 Simulator v2026 - Intel 8085 Microprocessor Trainer

> **A browser-based Intel 8085 learning environment that recreates a trainer kit, with editable registers and memory plus an integrated instruction emulator.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felix-westfv1600/8085-simulator-2026?style=flat-square)](https://github.com/felix-westfv1600/8085-simulator-2026)

---

<p align="center">
  <a href="https://felix-westfv1600.github.io/8085-simulator-2026/">
    <img src="https://img.shields.io/badge/Download-8085%20Simulator%20Latest-brightgreen?style=for-the-badge" alt="Download 8085 Simulator">
  </a>
</p>

> **[Download 8085 Simulator v2026](https://felix-westfv1600.github.io/8085-simulator-2026/)**

---

[Download Latest Build](https://felix-westfv1600.github.io/8085-simulator-2026/)

---

## What Is 8085 Simulator?

8085 Simulator provides a browser-based trainer kit for studying and experimenting with the Intel 8085 microprocessor. Its visual controls and built-in tools let you view or change memory, inspect registers, and execute programs without requiring physical trainer hardware.

The project uses HTML and JavaScript and is intended for learners, teachers, and anyone reviewing 8085 programming fundamentals. Its layout follows the style of a traditional hardware trainer while remaining practical to use from desktop and mobile browsers.

---

## Highlights

- Trainer kit-inspired visual control interface
- Seven-segment LED output for program feedback
- On-screen hexadecimal keypad for entering values
- Simulated 64 KB memory space
- Facilities for examining and changing memory
- Facilities for examining and changing registers
- Native emulator for 8085 instructions
- Program execution beginning at any memory address
- Responsive design for mobile screens
- Keyboard shortcuts for convenient control

---

## Getting Started

1. Obtain the source by cloning the repository:
   - `git clone https://github.com/felix-westfv1600/8085-simulator-2026.git
2. Change to the project directory:
   - `cd 8085-simulator`
3. Open the HTML entry file in a modern browser.
   - It can be opened as a local file, or you can use a local server for a more consistent development experience.

For example, start a basic local server with:
- `python -m http.server`

Open the local URL reported by the terminal.

---

## Using the Simulator

1. Start the application in a modern web browser.
2. Enter hexadecimal data through the virtual keypad or supported keyboard shortcuts.
3. Examine memory and update locations when required.
4. Check or change register values before running code.
5. Choose the required starting address and execute the program.
6. Follow the simulated output while testing 8085 instructions and program behavior.

A common practice sequence is:

- Place the required values in memory
- Configure the registers
- Start execution at the selected address
- Monitor the resulting 8085 state

---

## Configuration and Customization

The browser interface manages the simulator's primary state, including memory contents, register data, and execution status.

Running the project locally does not require a separate configuration file. To customize the application, edit the HTML and JavaScript files located in the project directory.

---

## System Requirements

- A current web browser
- Browser support for HTML and JavaScript
- Sufficient browser memory or local storage for smooth simulator operation
- An optional local web server for development or convenient file serving

---

## Frequently Asked Questions

**What is the first step?**  
Open the simulator in a browser, then enter hexadecimal values with the on-screen keypad or your keyboard.

**Can I change memory and register values?**  
Yes. The interface allows both memory contents and register state to be inspected and edited.

**Can execution begin at more than one address?**  
Yes. Programs may be run from any location in the simulated memory.

**Will it work on a phone or tablet?**  
The responsive interface is intended for mobile-sized displays as well as desktop browsers.

**How are new versions provided?**  
Updates are made available through the repository and the associated download page.

**What should I do if the interface renders incorrectly?**  
Use a current browser and reload the page. If the issue continues, try serving the project through a local web server.

---

## License

This project is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
