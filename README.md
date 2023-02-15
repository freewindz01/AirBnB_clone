A team project by Audu Sundday and Ejembi Sunday

Welcome to the AirBnB clone project!

BACKGROUND CONTEXT

First step: A command interpreter was written to manage this objects.

This is the first step towards building my first full web application: The AirBnB clone is a project I intend to implement in subsequent projects such as; *HTML/CSS templating *Database storage *API, front-end integration…

Each task is linked to help:

Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances.

Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel

Create the first abstracted storage engine of the project: File storage.

Create all unittests to validate all our classes and storage engine.

Execution Your shell should work like this in interactive mode:

$ ./console.py (hbnb) help

Documented commands (type help ):
EOF help quit

(hbnb) (hbnb) (hbnb) quit $ But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py (hbnb)

Documented commands (type help ):
EOF help quit (hbnb) $ $ cat test_help help $ $ cat test_help | ./console.py (hbnb)

Documented commands (type help ):
EOF help quit (hbnb) $ All tests should also pass in non-interactive mode: $ echo "python3 -m unittest discover tests" | bash# AirBnB_clone
