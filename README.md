# Perseus Tokenization

Canonical tokenization and machine-generated morphological analysis for
texts in the Perseus Digital Library.

## How to use

Clone the repository (or perform a partial checkout on the part that you need).
The files are plain JSON that have been compressed with [`zstd`](https://github.com/facebook/zstd).
Each file corresponds to a chunk of text as determined by the `citeStructure[@xml:id='CTS']` in the
Perseus Digital Library Code [repositories](https://github.com/PerseusDLCode).

Every token has been assigned a CTS URN, so you can use CTS-style citations
to further enrich these data for your own purposes.

## LICENSE

MIT License

Copyright (c) 2026 Perseus Digital Library

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

