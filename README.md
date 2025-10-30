# SDML language highlighter for highlight.js

![SDML Logo Text](https://raw.githubusercontent.com/sdm-lang/.github/main/profile/horizontal-text.svg)

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js. You'll use the minified version found in the `dist` directory. This
module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-sdml/dist/sdml.min.js"></script>
<script type="text/javascript">
  hljs.initHighlightingOnLoad();
</script>
```

### With Node or another build system

If you're using Node, Webpack, Rollup, Browserify, etc, simply require the language module, then register it with
Highlight.js.

```javascript
var hljs = require('highlightjs');
var hljsChaos = require('highlightjs-chaos');

hljs.registerLanguage("chaos", hljsChaos);
hljs.initHighlightingOnLoad();
```

## License(s)

The contents of this repository are made available under the following
licenses:

### Apache-2.0

> ```text
> Copyright 2025 Simon Johnston <johnstonskj@gmail.com>
> 
> Licensed under the Apache License, Version 2.0 (the "License");
> you may not use this file except in compliance with the License.
> You may obtain a copy of the License at
> 
>     http://www.apache.org/licenses/LICENSE-2.0
> 
> Unless required by applicable law or agreed to in writing, software
> distributed under the License is distributed on an "AS IS" BASIS,
> WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
> See the License for the specific language governing permissions and
> limitations under the License.
> ```

See the enclosed file [LICENSE-Apache](https://github.com/sdm-lang/highlight-js-sdml/blob/main/LICENSE-APACHE).

### MIT

> ```text
> Copyright 2025 Simon Johnston <johnstonskj@gmail.com>
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the “Software”), to deal
> in the Software without restriction, including without limitation the rights to
> use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
> the Software, and to permit persons to whom the Software is furnished to do so,
> subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
> INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
> PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
> HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
> OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
> SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
> ```

See the enclosed file [LICENSE-MIT](https://github.com/sdm-lang/highlight-js-sdml/blob/main/LICENSE-MIT).

### Contributions

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.

## Changes

TBD

## Development

<https://highlightjs.readthedocs.io/en/latest/language-contribution.html>
<https://github.com/highlightjs/highlight.js/blob/master/extra/3RD_PARTY_QUICK_START.md>

## Changes

TBD
