# Python project template
This repository contain basic structe that may follow for any kinds of python projects

## Project structure
```bash
python-project-template/
├── Doc
│   └── documentation.md
├── examples
│   ├── hello.py
│   └── __init__.py
├── projectname
│   ├── audio
│   │   ├── __init__.py
│   │   └── read_audio.py
│   ├── bar.py
│   ├── foo.py
│   ├── __init__.py
│   └── utils
│       ├── grok.py
│       ├── __init__.py
│       └── spam.py
├── README.md
└── tests
    ├── __init__.py
    ├── test_bar.py
    ├── test_foo.py
    └── test_read_audio.py
```

## How to run any module 
You can run any module from `python-project-template` directory

### To test bar.py
`python -m tests.test_bar`

### To test foo.py
`python -m tests.test_foo`

### To run examples
`python -m examples.hello`

### To test audio
`python -m tests.test_read_audio`

## Resources
- [The hitchhiker's guide to python to structure your project](https://docs.python-guide.org/writing/structure/)
- [Guide to python modules](https://docs.python.org/3/tutorial/modules.html)
