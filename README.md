# 6502-QR-code-generator
A simple DASM assembler library for creating small QR codes

## Introduction
This project provides a simple QR code generator for the 650x family. 

Note: 
The code is mostly specifically taylored for the Atari 2600 and a version 2 QR code. Other platforms or QR code versions have **not** been tested. But it should be adaptable without too major problems.

If you make use of my code or have questions, please let me know.

## Features
- easy to use DASM macros
- assembler switches to taylor generator to your needs
- code size optimized for minimal RAM and ROM space 
- all eight mask pattern supported
- Atari 2600 demo code (randomly generates some Atari 2600 related messages)
- generator code for Reed-Solomon ECC generator polygons accompanied

## Limitations
- only small, single block QR codes supported
- only byte mode supported
- no automatic mask pattern evaluation
- tested only for version 2, level L and M QR codes (25x25)

## License
Copyright © 2021 Thomas Jentzsch. (GPLV3 License)

This code is released under the GPLV3 license.

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The Software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the Software or the use or other dealings in the Software.
