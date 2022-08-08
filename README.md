# WilyPixel's .gitignores

A set of .gitignore files I use very often.

These are generated using the
[.gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)
extension for VS Code using the following templates as a base
(along with project/language specific templates):
`visualstudiocode`, `linux`, `emacs`, `macos`, `vim`, `windows`.

Overkill, perhaps, but it covers the most common OSs and editors used today.

I've also made some additional custom rules and modifications:

- Added a `/scratch/` rule for all .gitignore files. I reserve this directory
  for storing notes, snippets, etc.
- Added a `.env[0-9]*/` rule in `python.gitignore` in order to ignore additional
  virtual environments I use for testing (eg. env2,env39, etc.)
- Uncommented `.python-version` that was commented out in the original generated
  file.
