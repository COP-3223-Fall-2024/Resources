# Pre-requisites

Please make sure you know everything within [this document]()

This section will jumpstart you onto your first code compilation/execution.

## Required Compiler

If you are using a text editor, you will need the GCC compiler. You can follow the [instructions here](https://code.visualstudio.com/docs/cpp/config-mingw) for Windows.

For mac or linux users, it should be pre-installed. If not, I'm sure google is a search away. 

### C Programming

Make every file you make has the following format:
- `file_name.c`
- The `.c` is the extension for C files

Feel free to use features provided by your IDE or extensions provided by your code editor.

**Please refrain from using any ChatGPT or AI related extension. Yes it will code for you but you will not learn and are at risk of failing the FE later on.**

### IDE Usage

For IDEs, to compile and run a C program, click Build → Build and run to compile and build your C program, alternatively use the shortcut key F9.

In case, your program contains any errors. Error messages are shown in the Build messages tab below the code editor.

### Text Editor Usage

For text editors, make sure you have GCC compiler installed and ready for use on your computer's terminal or command prompt.

To compile, please run the following command:
- `gcc your_file_name.c -o any_word_here`
- replace `your_file_name` with the actual file name
- replace `any_word_here` with your file name or something of your choosing

To execute, please run the following command:
- `./any_word_here`

#### Exercise

Complete level 1's hello_world.c file such that it simply prints a single line to the output that says `Hello World!`