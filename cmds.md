
## Shell

- Search files for a string recursively from current dir: `grep -r "string to search for in files" .`
- Search files for a string recursively from current dir, but constrain recursion depth: `find . -maxdepth 4 -type f | xargs grep "string to search for in files"`

## Latex
- compile a latex file, render it as a pdf and watch for changes: `latexmk -pvc -pdf`
