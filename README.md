# Markdown Highlighting Aliases

The following aliases, when placed after the opening triple backticks of a code block, will give the enclosed code proper syntax highlighting. This list works for most implementations of Markdown, __*including Discord*__.

## Table of Contents

* [How To Use](#how-to-use-aliases)
* [The List](#the-list)
* [Sources](#source)
* [Legal](#legal)

## How To Use Aliases

Using the following syntax (remember to use backticks, not quotations)

\`\`\`somelanguage  
foo_dict = {  
&nbsp;&nbsp;&nbsp;&nbsp;"bar": "cat",  
&nbsp;&nbsp;&nbsp;&nbsp;"baz": "dog",  
&nbsp;&nbsp;&nbsp;&nbsp;"qux": "ferret"  
}  
\`\`\`

Generates the following syntax highlighting

```py
foo_dict = {
    "bar": "cat",
    "baz": "dog",
    "qux": "ferret"
}
```

## The List

| Language                | Aliases                |
| :-----------------------| :--------------------- |
| 1C                      | 1c                     |
| ABNF                    | abnf                   |
| Access logs             | accesslog              |
| Ada                     | ada                    |
| Arduino (C++ w/Arduino libs) | arduino, ino           |
| ARM assembler           | armasm, arm            |
| AVR assembler           | avrasm                 |
| ActionScript            | actionscript, as       |
| AngelScript             | angelscript, asc       |
| Apache                  | apache, apacheconf     |
| AppleScript             | applescript, osascript |
| Arcade                  | arcade                 |
| AsciiDoc                | asciidoc, adoc         |
| AspectJ                 | aspectj                |
| AutoHotkey              | autohotkey             |
| AutoIt                  | autoit                 |
| Awk                     | awk, mawk, nawk, gawk  |
| Bash                    | bash, sh, zsh          |
| Basic                   | basic                  |
| BNF                     | bnf                    |
| Brainfuck               | brainfuck, bf          |
| C#                      | csharp, cs             |
| C                       | c, h                   |
| C++                     | cpp, hpp, cc, hh, c++, h++, cxx, hxx |
| C/AL                    | cal                    |
| Cache Object Script     | cos, cls               |
| CMake                   | cmake, cmake.in        |
| Coq                     | coq                    |
| CSP                     | csp                    |
| CSS                     | css                    |
| Cap’n Proto             | capnproto, capnp       |
| Clojure                 | clojure, clj           |
| CoffeeScript            | coffeescript, coffee, cson, iced |
| Crmsh                   | crmsh, crm, pcmk       |
| Crystal                 | crystal, cr            |
| D                       | d                      |
| Dart                    | dart                   |
| Delphi                  | dpr, dfm, pas, pascal  |
| Diff                    | diff, patch            |
| Django                  | django, jinja          |
| DNS Zone file           | dns, zone, bind        |
| Dockerfile              | dockerfile, docker     |
| DOS                     | dos, bat, cmd          |
| dsconfig                | dsconfig               |
| DTS (Device Tree)       | dts                    |
| Dust                    | dust, dst              |
| EBNF                    | ebnf                   |
| Elixir                  | elixir                 |
| Elm                     | elm                    |
| Erlang                  | erlang, erl            |
| Excel                   | excel, xls, xlsx       |
| F#                      | fsharp, fs             |
| FIX                     | fix                    |
| Fortran                 | fortran, f90, f95      |
| G-Code                  | gcode, nc              |
| Gams                    | gams, gms              |
| GAUSS                   | gauss, gss             |
| Gherkin                 | gherkin                |
| Go                      | go, golang             |
| Golo                    | golo, gololang         |
| Gradle                  | gradle                 |
| GraphQL                 | graphql                |
| Groovy                  | groovy                 |
| HTML, XML               | xml, html, xhtml, rss, atom, xjb, xsd, xsl, plist, svg |
| HTTP                    | http, https            |
| Haml                    | haml                   |
| Handlebars              | handlebars, hbs, html.hbs, html.handlebars        |
| Haskell                 | haskell, hs            |
| Haxe                    | haxe, hx               |
| Hy                      | hy, hylang             |
| Ini, TOML               | ini, toml              |
| Inform7                 | inform7, i7            |
| IRPF90                  | irpf90                 |
| JSON                    | json                   |
| Java                    | java, jsp              |
| JavaScript              | javascript, js, jsx    |
| Julia                   | julia, julia-repl      |
| Kotlin                  | kotlin, kt             |
| LaTeX                   | tex                    |
| Leaf                    | leaf                   |
| Lasso                   | lasso, ls, lassoscript |
| Less                    | less                   |
| LDIF                    | ldif                   |
| Lisp                    | lisp                   |
| LiveCode Server         | livecodeserver         |
| LiveScript              | livescript, ls         |
| Lua                     | lua                    |
| Makefile                | makefile, mk, mak, make |
| Markdown                | markdown, md, mkdown, mkd |
| Mathematica             | mathematica, mma, wl   |
| Matlab                  | matlab                 |
| Maxima                  | maxima                 |
| Maya Embedded Language  | mel                    |
| Mercury                 | mercury                |
| MIPS Assembler          | mips, mipsasm          |
| Mizar                   | mizar                  |
| Mojolicious             | mojolicious            |
| Monkey                  | monkey                 |
| Moonscript              | moonscript, moon       |
| N1QL                    | n1ql                   |
| NSIS                    | nsis                   |
| Nginx                   | nginx, nginxconf       |
| Nim                     | nim, nimrod            |
| Nix                     | nix                    |
| OCaml                   | ocaml, ml              |
| Objective C             | objectivec, mm, objc, obj-c, obj-c++, objective-c++ |
| OpenGL Shading Language | glsl                   |
| OpenSCAD                | openscad, scad         |
| Oracle Rules Language   | ruleslanguage          |
| Oxygene                 | oxygene                |
| PF                      | pf, pf.conf            |
| PHP                     | php                    |
| Parser3                 | parser3                |
| Perl                    | perl, pl, pm           |
| Plaintext               | plaintext, txt, text   |
| Pony                    | pony                   |
| PostgreSQL & PL/pgSQL   | pgsql, postgres, postgresql |
| PowerShell              | powershell, ps, ps1    |
| Processing              | processing             |
| Prolog                  | prolog                 |
| Properties              | properties             |
| Protocol Buffers        | proto, protobuf        |
| Puppet                  | puppet, pp             |
| Python                  | python, py, gyp        |
| Python profiler results | profile                |
| Python REPL             | python-repl, pycon     |
| Q                       | k, kdb                 |
| QML                     | qml                    |
| R                       | r                      |
| ReasonML                | reasonml, re           |
| RenderMan RIB           | rib                    |
| RenderMan RSL           | rsl                    |
| Roboconf                | graph, instances       |
| Ruby                    | ruby, rb, gemspec, podspec, thor, irb |
| Rust                    | rust, rs               |
| SAS                     | SAS, sas               |
| SCSS                    | scss                   |
| SQL                     | sql                    |
| STEP Part 21            | p21, step, stp         |
| Scala                   | scala                  |
| Scheme                  | scheme                 |
| Scilab                  | scilab, sci            |
| Shell                   | shell, console         |
| Smali                   | smali                  |
| Smalltalk               | smalltalk, st          |
| SML                     | sml, ml                |
| Stan                    | stan, stanfuncs        |
| Stata                   | stata                  |
| Stylus                  | stylus, styl           |
| SubUnit                 | subunit                |
| Swift                   | swift                  |
| Tcl                     | tcl, tk                |
| Test Anything Protocol  | tap                    |
| Thrift                  | thrift                 |
| TP                      | tp                     |
| Twig                    | twig, craftcms         |
| TypeScript              | typescript, ts, tsx, mts, cts |
| VB.Net                  | vbnet, vb              |
| VBScript                | vbscript, vbs          |
| VHDL                    | vhdl                   |
| Vala                    | vala                   |
| Verilog                 | verilog, v             |
| Vim Script              | vim                    |
| X++                     | axapta, x++            |
| x86 Assembly            | x86asm                 |
| XL                      | xl, tao                |
| XQuery                  | xquery, xpath, xq, xqm |
| YAML                    | yml, yaml              |
| Zephir                  | zephir, zep            |
<!-- LANGLIST_END -->

## Alias Overlap

If you are using either of these languages at the same time please be sure to
use the full name and not the alias to avoid any ambiguity.

| Language                | Overlap                |
| :-----------------------| :--------------------- |
| SML                     | ml                     |
| OCaml                   | ml                     |
| Lasso                   | ls                     |
| LiveScript              | ls                     |

## Source

The source of this information is obtained from the JavaScript library that Markdown itself uses, called [highlight.js](https://github.com/highlightjs/highlight.js/blob/main/SUPPORTED_LANGUAGES.md).  

Please note that a substantial amount of languages listed within the the source are third-party lexers and are not officially packaged within highlight.js. As a result, those languages *do not work* within Markdown, unless explicitly downloaded and configured.

## Legal

I do not own the rights to `highlight.js`, its name, or its brand. I do not own the rights to any of the third-party lexers or parsers mentioned in this list. You can find the sources's license under `highlightjs-LICENSE.txt`.
