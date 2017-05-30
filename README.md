# Fix The Web

> Let's fix it together.. One line at a time!

## What is this?

If you are [persnickety](https://www.merriam-webster.com/dictionary/persnickety) like I am, you can easily fix quite a few things and at the same time contribute to your favorite project. It's never too late to start contributing instead of just consuming.

## Contents

- [EditorConfig]('#editorconfig')
- [Search and Replace]('#search-and-replace')

## EditorConfig

> No matter how many people contrubte to the code, it should always look like it was written by one person.

And with that in mind it's a good idea to add the [EditorConfig](http://editorconfig.org/) into your favorite project.

Create a new file in the root called `.editorconfig` by respecting the coding styles that already applied. Here is an example:

```bash
# editorconfig.org

root = true

[*]
charset = utf-8
end_of_line = lf
indent_size = 2
indent_style = space
insert_final_newline = true
trim_trailing_whitespace = true
```

Get ideas from: [React](https://github.com/facebook/react/blob/master/.editorconfig), [Visual Studio Code](https://github.com/Microsoft/vscode/blob/master/.editorconfig), [Angular JS](https://github.com/angular/angular.js/blob/master/.editorconfig) and [gae-init](https://github.com/gae-init/gae-init/blob/master/.editorconfig).

## Search and Replace

### Recommended renames

We recommend to submit each of the following possible fixes in a separate Pull Request.

- `Github` => `GitHub`
- `Javascript` => `JavaScript`
- `OSX`, `OS X`, `MacOS` => `macOS`

### Yes, but how?

1. Find your [favorite project](https://github.com/trending) and Fork it
2. Clone it and open the project in your [favorite editor](https://code.visualstudio.com/)
3. Search all for exact match of `Javascript` and replace it with `JavaScript`
4. Create a new branch: `git checkout -b fix-case`
5. Commit all changes: `git commit -am 'Fix case: Javascript to JavaScript'`
6. Push your changes: `git push origin fix-case`
7. Create pull request to the [original project](https://github.com/facebook/react/pull/9797)
8. Be polite!
