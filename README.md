# crystal-palace-vsc

This is a Visual Studio Code (VSC) extension that aims to provide an implementation of the Crystal Palace Specification File grammar, based on the documentation found [here](https://tradecraftgarden.org/docs.html#specfiles).

## Features

The extension provides basic syntax highlighting for the various Crystal Palace commands.

![Syntax Highlighting](images/syntax-hightlighting.png)

### Snippets

It also provides the following snippets:

| prefix | body |
|--------|------|
| ah | addhook "MOD$Func" "hook" |
| ahc | addhook "MOD$Func" |
| att | attach "MOD$Func" "hook" |
| dfr | dfr "resolver" "method" |
| dfre | dfr "resolver" "method" "M1, M2" |
| ef | exportfunc "func" "__tag_func" |
| fh | filterhooks $DLL |
| lf | linkfunc "symbol" |
| mc | make coff |
| mo | make object |
| mp | make pic |
| ml | mergelib "lib.x##.zip" |
| rs | run "foo.spec" |

**Enjoy!**
