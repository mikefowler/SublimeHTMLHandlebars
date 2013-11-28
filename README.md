**Adds reliable, no-nonsense [Handlebars][1] syntax to Sublime Text. Supports `.handlebars`, and `.hbs` files.**

Credit goes to [adamchainz's SublimeHTMLMustache project][2] for the original syntax files, updated to support Handlebars instead.

## Snippets

After setting the syntax to "HTML (Handlebars)" you will be able to use the following snippets:

Trigger                 | Result
----------------------- | ----------------------
`if`                    | `{{#if context}} ... {{/if}}`
`ifelse`                | `{{#if context}} ... {{else}} ... {{/if}}`
`unless`                | `{{#unless context}} ... {{/unless}}`
`each`                  | `{{#each context}} ... {{/each}}`
`with`                  | `{{#with context}} ... {{/with}}`
`comment`               | `{{! comment }}`
`partial`               | `{{> partial}}`
`variable`              | `{{variable}}`
`variable-safe`         | `{{{variable}}}`

## License

SublimeHTMLHandlebars is released under the MIT license.

Copyright (c) 2013 Mike Fowler <mike@mikefowler.me>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[1]: http://handlebarsjs.com
[2]: https://github.com/adamchainz/SublimeHTMLMustache
