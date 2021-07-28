# Super Mario
This is super mario game implemented in c++ language which was one of our project in Advanced Programming course (Spring 98).

## Intoduction
This is a minimal, c++ implementation of the famous and nostalgic game SuperMario, which was chosen as a course project for the Advanced Programming course of the Computer Engineering major of University of Tehran, on the 2019 spring semester.

The repository would also be shown to the students as an example of a "good-enough" design to help guide them towards better designs.

This project is built using the <a href="https://github.com/UTAP/RSDL">RSDL</a> (Ramtin's Simple DirectMedia Layer) library, which is a library developed to help students use the SDL library through a simpler and more object-oriented interface.


## How to run?
To play this game, you need to do the typical steps for running any c-based project. First, clone the repository into a directory which we will call ‍‍‍`<mario-dir>` from now on. Then, change directory to `<mario-dir>/src`. Then run
```
make
```

to create the executable. Then run
```
./mario.out <level-file-address>
```
to play the game. The game currently has only one level, and it will default to that one level if the executable is called without any arguments.

*Made by Amirhossein Abaskohi*
