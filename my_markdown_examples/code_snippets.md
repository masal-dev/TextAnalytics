# Code snippets
To format the text as `code`, so with a monospaced font, it must be enclosed between 2 backticks: `

To show a block of code we must enclose it between 2 triple backtick sequences: \```

Like this:\
\```
```
def ReverseGen(data):
    for i in range(len(data)-1, -1, -1):
        yield data[i]
```
\```

## Formatting the code according to a specific language
The code above is formatted as monospaced but we can also obtain a formatting according to a specific language.\
To achieve that we have to add the language name just after the first line of 3 backticks separated by a space:

I.e. for Python:\
\``` python
``` python
def ReverseGen(data):
    for i in range(len(data)-1, -1, -1):
        yield data[i]
```
\```
