| Filetype        | Extension            | Notes                                      | Parser Name         |
| --------------  | -------------------- | -------------------------------------------| ------------------- |
| C#              | `.cs`                | Supports `// and /* */` comments.          | defaultParser       |
| C++/C           | `.cpp` `.c` `.h`     | Supports `// and /* */` comments.          | defaultParser       |
| Coffee-React    | `.cjsx`              | Supports `#` comments.                     | coffeeParser        |
| Coffeescript    | `.coffee`            | Supports `#` comments.                     | coffeeParser        |
| Crystal         | `.cr`                | Supports `#` comments.                     | coffeeParser        |
| CSon            | `.cson`              | Supports `#` comments.                     | coffeeParser        |
| CSS             | `.css`               | Supports `/* */` comments.                 | defaultParser       |
| EJS             | `.ejs`               | Supports `<!-- -->` and `<%# %>`           | ejsParser           |
| Erb             | `.erb`               | Supports `<!-- -->` and `<%# %>`           | ejsParser           |
| Erlang          | `.erl` `.hrl`        | Supports `%` comments.                     | erlangParser        |
| Go              | `.go`                | Supports `// and /* */` comments.          | defaultParser       |
| Haml            | `.haml`              | Supports `/ -# <!-- --> and <%# %>`        | twigParser          |
| Handlebars      | `.hbs` `.handlebars` | Supports `{{! }}` and `{{!-- --}}`         | hbsParser           |
| Haskell         | `.hs`                | Supports `--`                              | haskellParser       |
| Hogan           | `.hgn` `.hogan`      | Supports `{{! }}` and `{{!-- --}}`         | hbsParser           |
| HTML            | `.html` `.htm`       | Supports `<!-- -->`                        | twigParser          |
| Jade            | `.jade` `.pug`       | Supports `//` and `//-` comments.          | jadeParser          |
| Java            | `.java`              | Supports `// and /* */` comments           | defaultParser       |
| Javascript      | `.js` `.es` `.es6`   | Supports `// and /* */` comments           | defaultParser       |
| Julia           | `.jl`                | Supports `"""` and `#` comments.           | pythonParser        |
| Jsx             | `.jsx`               | Supports `// and /* */` comments.          | defaultParser       |
| Kotlin          | `.kt`                | Supports `// and /* */` comments.          | defaultParser       |
| Latex           | `.tex`               | Supports `\begin{comment}` and `%` comments| latexParser         |
| Less            | `.less`              | Supports `// and /* */` comments.          | defaultParser       |
| Lua             | `.lua`               | Supports `--` and `--[[ ]]` comments.      | haskellParser       |
| Markdown        | `.markdown`, `.md`   | Supports `<!-- -->`                        | twigParser          |
| Mustache        | `.mustache`          | Supports `{{! }}` and `{{!-- --}}`         | hbsParser           |
| Nunjucks        | `.njk`               | Supports `{#  #}` and `<!-- -->`           | twigParser          |
| Objective-C     | `.m`                 | Supports `// and /* */` comments           | defaultParser       |
| Objective-C++   | `.mm`                | Supports `// and /* */` comments           | defaultParser       |
| Pascal          | `.pas`               | Supports `// and { }` comments.            | pascalParser        |
| Perl            | `.pl`, `.pm`         | Supports `#` comments.                     | coffeeParser        |
| PHP             | `.php`               | Supports `// and /* */` comments.          | defaultParser       |
| CakePHP views   | `.ctp`               | Supports `// and /* */` comments.          | defaultParser       |
| Protocol Buffer | `.proto`             | Supports `// and /* */` comments.          | defaultParser       |
| Python          | `.py`                | Supports `"""` and `#` comments.           | pythonParser        |
| Ruby            | `.rb`                | Supports `#` comments.                     | coffeeParser        |
| Rust            | `.rs`                | Supports `// and /* */` comments.          | defaultParser       |
| Sass            | `.sass` `.scss`      | Supports `// and /* */` comments.          | defaultParser       |
| Scala           | `.scala`             | Supports `// and /* */` comments.          | defaultParser       |
| Shell           | `.sh` `.zsh` `.bash` | Supports `#` comments.                     | coffeeParser        |
| SilverStripe    | `.ss`                | Supports `<%-- --%>` comments.             | ssParser            |
| SQL             | `.sql`               | Supports `--` and `/* */` comments         | defaultParser & haskellParser |
| Stylus          | `.styl`              | Supports `// and /* */` comments.          | defaultParser       |
| Swift           | `.swift`             | Supports `// and /* */` comments.          | defaultParser       |
| Svelte          | `.svelte`            | Supports `//` `/* */` `<!-- -->` comments. | twigParser          |
| Twig            | `.twig`              | Supports `{#  #}` and `<!-- -->`           | twigParser          |
| Typescript      | `.ts`, `.tsx`        | Supports `// and /* */` comments.          | defaultParser       |
| Vue             | `.vue`               | Supports `//` `/* */` `<!-- -->` comments. | twigParser          |
| Yaml            | `.yaml` `.yml`       | Supports `#` comments.                     | coffeeParser        |