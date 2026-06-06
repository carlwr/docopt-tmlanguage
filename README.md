# docopt.tmLanguage

[![npm](https://img.shields.io/npm/v/@carlwr/docopt-tmlanguage?logo=npm)](https://www.npmjs.com/package/@carlwr/docopt-tmlanguage)
[![license](https://img.shields.io/npm/l/@carlwr/docopt-tmlanguage)](https://github.com/carlwr/docopt-tmlanguage/blob/main/LICENSE)

A TextMate grammar for _docopt-style command synopsis notation_ — which may look like e.g.:

```
cat [OPTION]... [FILE]...

cd [ -qsLP ] {+|-}n

prog -a [-bc -e param] --arg0 val0 --arg1=val1

prog <thing> [[+-]feature ...]
```

The closest to an authoritative "docopt spec" would be [POSIX _12.1 Utility Argument Syntax_][posix-12.1] or [docopt.org]. The grammar generally supports the syntax each of these specify, but also accommodates other forms commonly seen in the wild, e.g. the `{+|-}` form.

## AI/human authorship

This `README.md` file [is written by](./AGENTS.md) me, Carl, a human developer. The grammar itself is written by LLMs. 

## Similar/related grammars

- https://github.com/Vallentin/vscode-bnf (`bnf.tmLanguage`)
- https://github.com/victor-gp/cmd-help-sublime-syntax (`text.cmd-help`)

## References

- [POSIX _12.1 Utility Argument Syntax_][posix-12.1]
- [docopt.org]

[posix-12.1]: https://pubs.opengroup.org/onlinepubs/9799919799/
[docopt.org]: http://docopt.org/
