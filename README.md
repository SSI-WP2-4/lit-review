# lit-review
Deliverable 1: overview of learnings from earlier ESSNET (TSS1) projects, literature

## Contributing
Please feel free to add any links to literature that you find useful. If there's no good way to do so by uploading or editing a file, you can just drop it into the [M6 Deliverable Project](https://github.com/orgs/SSI-WP2-4/projects/1)

## Using diff for word files
Interested parties can version and diff word files using the .gitattributes document in this repository. Other steps necessary if you want to do this:

1. [Download and install Pandoc](https://pandoc.org/installing.html)
2. Edit .gitconfig file (on Windows "C:\Users\<User>\.gitconfig", on linux/Mac "~/.gitconfig") to contain the following text:

```
[diff "pandoc"]
     textconv=pandoc --to=markdown
     prompt = false
[alias]
     wdiff = diff --word-diff=color --unified=1
```

## License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
