rn-format
=========
rn-format is a wrapper around clang-format.

It invokes clang-format with a built-in formatting style, allowing it
to be used without any external .clang-format file.

It also performs additional reformatting not supported by clang-format.

It is distributed under the MIT licence.


Usage
-----
rn-format [--rewrite] [--clang] PATH ...

