This is a prototype for separating and packaging
[Triton](https://github.com/ptillet/triton) source code files.

Any files in the `triton/` directory that end in `.txt` will be automatically
parsed into strings and made importable via their basename. So for example,
`triton/cats.txt` is importable via `from triton import cats`.

See `driver.py` for more usage information.
