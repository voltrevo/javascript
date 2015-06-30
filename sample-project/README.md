# sample-project

Projects should have the following structure:

```
.gitignore
.jscsrc
.jshintrc
README.md
package.json
src/
spec/
```

## .gitignore

Avoids git noise and helps prevent accidentally committing things that don't belong in git.

Should contain at least:

```
node_modules
*.log
```

## .jscsrc

Configuration for jscs. Should match https://github.com/opentok/javascript/blob/master/linters/jscsrc.

## .jshintrc

Configuration for jshint. Should match https://github.com/opentok/javascript/blob/master/linters/jshintrc.

## README.md

Essential information about your project. Consider also creating README.md files in subdirectories. The top-level README.md should start with how to use the project and how to test it.

## package.json

Project metadata. Provides npm integration and also used by other tools such as 
