# TODO Finder #
Just keeping track of an idea. Parse your source code for comments starting with "TODO" and automatically append them to the containing project's README.md.
Details:
- Add as hook on git commit.
- Recognize when an existing TODO has merely been updated
- Later on, add capability to manage TODOs with small cli tool (or even better, integrate with `todo.txt`)
- "Independent" of language
    - Will need to capture each language's comment style
