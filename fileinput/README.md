# fileinput

`fileinput` implements the typical POSIX / GNU interface:

- read from files with filenames in stdin[1:], one by one
- if none is given, read from stdin.

Run the tests:

    ./test_main.py

Understand what `main.py` does:

    ./main.py a b
    ./main.py b a
    echo 'c\nc2' | ./main.py
    echo 'c\nc2' | ./main.py a b
