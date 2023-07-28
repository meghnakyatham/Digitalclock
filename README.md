# Digitalclock
# Console Clock Simulator

This is a simple C program that simulates a clock using the console output. The program prompts the user to set the initial time (hours, minutes, and seconds), and then continuously updates and displays the time in a loop, creating the illusion of a running clock.

## Getting Started

To run the clock simulator on your machine, follow these steps:

1. Ensure you have a C compiler installed on your system. This program was tested with GCC (GNU Compiler Collection).

2. Clone or download this repository to your local machine.

3. Open a terminal or command prompt and navigate to the directory containing the source code file `clock_simulator.c`.

4. Compile the program using the following command:


5. After successful compilation, run the executable:

- On Windows, use: `clock_simulator.exe`
- On macOS or Linux, use: `./clock_simulator`

## Usage

When you run the program, it will prompt you to set the initial time for the clock. Enter the hours, minutes, and seconds when prompted, all separated by spaces. The program will validate the input to ensure it is within a valid range (hours <= 12, minutes <= 60, seconds <= 60). If the input is invalid, an error message will be displayed, and the program will exit.

Once the initial time is set, the clock simulator will start running and continuously display the updated time in the format `HH:MM:SS`. The clock will behave like a 12-hour format clock, so the hour hand will be in the range 1 to 12.

To stop the clock simulator, you can terminate the program by pressing `Ctrl+C` or closing the terminal/command prompt.

## Known Issues

There are no known issues with the current version of the clock simulator.

## Contributing

This is a simple project intended for educational purposes. Contributions are not expected, but if you have any suggestions or improvements, feel free to create an issue or fork the repository and submit a pull request.

## License

This clock simulator is open-source and distributed under the [MIT License](LICENSE). You can freely use, modify, and distribute the code as per the terms of the license.

