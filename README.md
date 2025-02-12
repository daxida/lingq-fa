
**F**orced **a**lignment: split audio (one or more files) to match text (one or more files).

This adapts [aeneas](https://github.com/readbeyond/aeneas) to be compatible with [LingQ](https://www.lingq.com/) format.

Even if you do not use LingQ yourself, you may be interested if want to match audio to text but you do not satisfy aeneas expected singlefile inputs. This instead should work with the following generic book structure:

```
book
├── texts
│   ├── text1.txt
│   └── text2.txt
└── audios
    ├── audio1.mp3
    ├── audio2.mp3
    └── audio3.mp3
```

Assuming that the contents of the merged texts should perfectly match the merged audios.

More details are available as docstrings. Only tested for greek and japanese.

## Install and run

```
# Install
pip install git+https://github.com/daxida/lingq-fa

# Replace this path with a path to your book
fa tests/fixtures/book

# More details at
fa --help
```
