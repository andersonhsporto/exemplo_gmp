# C template

This is a template for C projects. It uses 
[Make](https://www.gnu.org/software/make/) to compile the project.

### Structure

The project is structured as follows:

	.
	├── bin
	│   └── main
	├── include
	│   └── 0_folder
	│   │   └── teste.h
	│   └── 1_folder
	│       └── teste2.h
	└── src
	│   ├── 0_folder
	│   │   └── teste.c
	│   └── 1_folder
	│       └── teste2.c
	└── Makefile


### Makefile Description

#### Variables

- CXX = Compiler

- CXXFLAGS = Compiler flags

- NAME = Name of the executable

- SRC = Source files

- MAIN_HEADERS = Include files

- INCLUDE = Include directories


### Usage

To build the project, run `make` in the root directory.
To clean the project, run `make clean`.
To clean the project and binaries, run `make fclean`.
To recompile the project, run `make re`.

### License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

